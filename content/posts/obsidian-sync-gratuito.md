+++
title = 'Sincronizando Obsidian com Cloudflare R2'
date = 2024-10-14T10:29:46-03:00
draft = false
+++
--- 
## Requisitos:
- Plugin [RemotelySave](https://obsidian.md/plugins?id=remotely-save)
- Conta na Cloudflare 
	- Cartão de crédito (necessário pro cadastro)
	- [R2 Bucket](https://www.cloudflare.com/pt-br/developer-platform/r2/)
---

Sincronizar suas notas no Obsidian, entre as várias plataformas suportadas pelo aplicativo, costuma ser uma das maiores barreiras que os usuários tem ao mergulhar no incrível universo de possibilidades que o Obsidian oferece. Por um lado, a simplicidade e por outro as possibilidades quase ilimitadas que o aplicativo oferece.

Depois de tentar vários métodos, inclusive o oficial [Obsidian Sync](https://obsidian.md/sync), descobri que você pode usar a generosa oferta gratuita da Cloudlfare para conseguir sincronizar suas notas e arquivos. O plano `Padrão` do Obsidian Sync, limita o usuário a 1GB de armazenamento e um limite por arquivo de 5MB, que particularmente acho extremamente restritivo, considerando que a opção de plano `Plus`, o limite sobe para 200MB por arquivo, um aumento de 40x, e um cofre de 10GB de armazenamento.

Usando o método que vou compartilhar, você terá o armazenamento do plano `Plus` e sem a limitação de 200MB por arquivo, totalmente de graça! (até o momento da postagem).

Bom, vamos começar:

# Criando um R2 Bucket na Cloudflare 
Após a criação de sua conta na Cloudflare, na barra lateral, clique em `R2 Object Storage`:

![](https://files.catbox.moe/auvg7c.png)

Crie um Bucket:

![](https://files.catbox.moe/5m00ms.png)

Escolha um bom nome para o seu Bucket, **esse nome não pode ser alterado!** e clique em `Create bucket`.

![](https://files.catbox.moe/e1q0b9.png)

## Criando um API Token

Volte ao Overview R2 Object Storage e clique em `Manage R2 API Tokens` e crie um API Token:

![](https://files.catbox.moe/8gfl90.png)
![](https://files.catbox.moe/jzgroe.png)

Escolha um nome para o Token, nas Permissões escolha `Read & Write`, em seguida selecione seu `Bucket` na parte seguinte, fazendo com que seu API Token só tenha acesso a esse único `Bucket`, e por fim, crie o Token.
![](https://files.catbox.moe/3xqckt.png)

Na próxima tela, guarde de forma segura o:
- **Token value**
- **Access Key ID**
- **Secret Access Key**
- **Jurisdiction-Specific Endpoints for S3 Clients**

Esses são os dados que você vai colocar no seu Obsidian.

# Remotely Save Plugin 
Nesse momento, é fundamental configurar corretamente o plugin Remotely Save no seu Obsidian. Este processo só precisa ser realizado uma vez, já que o plugin oferece a opção de exportar suas configurações pré-definidas, você pode aproveitar essa oportunidade para definir as configurações de sincronização do jeito que você gosta.

### Configurações Iniciais
Após a instalação do [RemotelySave](https://obsidian.md/plugins?id=remotely-save), vá nas `Configurações` > `Plugins Não Oficiais` > `Remotely Save` e escolha `S3 & Compatible` e preencha os dados que você salvou anteriormente:

![](https://files.catbox.moe/pg8dtp.png)

### Configurações Básicas
Feito isso, configure as opções básicas de sincronização, particularmente acho essas as ideais, com sincronização ao iniciar o aplicativo e sincronização feita a cada modificação:

![](https://files.catbox.moe/ocde91.png)

### Exportando configurações
Por fim, você pode (e deve) exportar suas configurações para que não precise fazer esse processo novamente em outros dispositivos:

![](https://files.catbox.moe/s5x2qr.png)

![](https://files.catbox.moe/zskdhi.png)

Obs.: Se acontecer algum erro ao fazer a primeira sincronização, é normal, o [RemotelySave](https://obsidian.md/plugins?id=remotely-save) por padrão coloca um limite de 50% dos itens, mas você pode desabilitar nas configurações do Plugin:

![](https://files.catbox.moe/4vjzmg.png)

**Lembre-se:** ao trabalhar com serviços em nuvem, é fundamental manter suas credenciais seguras e realizar backups regularmente para garantir a proteção dos seus dados, sincronização =/= backup!

Pronto! Agora você tem sincronização, similar ao Obsidian Sync oficial, de forma gratuita e com você no controle dos dados. E graças ao generoso plano gratúito da Cloudflare, você pode sincronizar MUITAS vezes ao dia.
