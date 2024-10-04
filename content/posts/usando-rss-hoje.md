+++
title = 'Usando Rss em 202X'
date = 2024-10-04T17:21:53-03:00
draft = false
+++

Imagina ter controle total sobre o que você lê e informações que recebe online. Essa é a ideia do RSS. Bom não necessariamente isso, mas gosto de pensar que é. 

O RSS é um formato simples que permite a você se inscrever em seus sites, blogs e podcasts favoritos e receber as últimas atualizações em um só lugar. Ao contrário das redes sociais, que controlam o que você vê através de algoritmos, o RSS coloca você no comando.

## Por que usar o RSS?

- Personalização: Crie suas próprias listas de leitura e organize as informações da forma que preferir.
- Economia de tempo: Evite perder tempo procurando por novas publicações em diferentes sites.
- Privacidade: Tenha controle sobre seus dados e evite a manipulação algorítmica.
- Conteúdo de qualidade: Descubra novos conteúdos e autores que se alinham aos seus interesses.

## "RSS, eu já ouvi falar disso"

Provavelmente sim, essa história vem desde os meados dos anos 90, com dedo do Netscape, a internet usa o protocolo RSS para se comunicar, e hoje com a ascensão da indie/small web, RSS volta com tudo, com mais de 1/3 da internet é movida por WordPress, que tem RSS nativo (basta colocar `/feed` no final da URL) e os Blogs Pessoais (igual esse que você está lendo agora!), RSS mostrou mais ainda sua relevância.

Com a decadência do Twitter/X, Instagram, TikTok e outras redes sociais que priorizam manter o usuário na plataforma por pela maior quantidade de tempo possível, ter controle sobre o que aparece na sua linha do tempo se se tornou uma regalia que poucos possuem. Desinformação desenfreada, conteúdos que não são do seu interesse, contas que você não seguiu e falta total de moderação, são só alguns dos motivos que fizeram uma boa parte da base de usuários dessas redes sociais migrarem para o Bluesky e Mastodon. 

Entretanto, com essa mudança, muitos usuários que também usavam essas redes sociais para acompanhar notícias e receber atualizações, das mais diversas fontes, se viram sem opções, muitos perfis não fizeram a mesma migração. 

É nesse momento que entra o RSS e seu leitor. Com ele você pode seguir as mais variadas fontes **de sua escolha**, e somente elas, nada de algoritmos decidindo por você o que deve ver, nada de abrir todas as fontes de notícias, uma por uma, para receber atualizações, basta abrir seu leitor RSS e todas as atualizações recentes de jornais, blogs, atualização de aplicativos, podcasts, perfis do Bluesky e Mastodon, canais do YouTube, comunidades do Reddit e **muitos** outros.

## Usando RSS

Para começar, usaremos o [RSSGuard](https://github.com/martinrotter/rssguard), ele funciona Windows, Linux e macOS.

![](https://github.com/martinrotter/rssguard/raw/master/resources/graphics/official_pictures/main-window-linux.png)

Após baixar e instalar (você encontra a última versão lançada [aqui](https://github.com/martinrotter/rssguard/releases/latest)), logo de cara ao abrir o RSSGuard, ele nos recebe com uma tela de opções, selecionaremos `RSS/ATOM`:

![](https://i.postimg.cc/pV9vQ9nT/Captura-de-tela-2024-10-04-113126.png)

E selecionar `Não` para adicionar os feeds recomendados:

![](https://i.postimg.cc/g2pPPNtX/Captura-de-tela-2024-10-04-113216.png)

Mude o layout para três painéis verticais:

![](https://i.postimg.cc/0NMgYFb4/image.png)

Por algum motivo, RSSGuard limita o tamanho das imagens na hora da leitura, mas é bem fácil corrigir isso, basta ir nas `ferramentas` > `configurações` > `feeds & artigos` > `artigos` e mude o valor no 3 ponto para 0 (zero).

![](https://files.catbox.moe/htbx78.png)

Isso só precisa ser feito uma vez, não consigo entender essa escolha, mas ainda bem que pode ser facilmente revertida.

Feito isso, adicionaremos nosso primeiro feed, clicando em `feed` > `adicionar item` > `adicionar novo feed`.  
![](https://files.catbox.moe/lb1hny.png)

Nesta nova janela, coloque a URL da página que você quer seguir, RSSGuard tentará achar o feed para você. Então, selecione um dos feeds e clique em `Importar feeds selecionados`
![](https://files.catbox.moe/87ylxa.png)

Agora só clicar no ícone de `Download` para que o RSSGuard busque os itens mais recentes nos feeds que você segue.

![](https://files.catbox.moe/twwcl8.png)

Prontinho, agora você tem seu feed para ler, sem propaganda, sem algoritmo e principalmente sem distrações!
![](https://files.catbox.moe/ngaenn.png "Gatinhos!")

Pronto! Simples (nem tanto) assim. Mas saber seguir um feed é só uma parte da história, a outra é qual feed seguir ou mesmo como encontrar feeds, para isso recomendo o [RSS Feed ASAP](https://rssfeedasap.com/), nem sempre você terá o RSSGuard aberto para buscar feeds para você.

E para encerrar deixarei algumas recomendações de feed e aplicativos leitores de RSS.


## Recomendações:
### Feeds

#### Blogs: 
- [The Digital Antiquarian](https://www.filfre.net/ "The Digital Antiquarian") ([Feed](https://www.filfre.net/feed/))
- [CD-ROM Journal](http://cdrom.ca/) ([Feed](http://cdrom.ca/feed.xml))
- [Blog SakugaBooru](https://blog.sakugabooru.com/)([Feed](https://blog.sakugabooru.com/feed/))

#### Revistas:
- [Revista Piauí](https://piaui.folha.uol.com.br/) ([Feed]( https://piaui.folha.uol.com.br/feed/))
- [Aeon](https://aeon.co/) ([Feed](https://aeon.co/feed))
- [Revista Cult](https://revistacult.uol.com.br/home/) ([Feed](https://aeon.co/feed))
- [Epoché Magazine](https://epochemagazine.org/) ([Feed](https://epochemagazine.org/feed/))

#### Canais do YouTube:
Colar a URL do canal no [RSS Feed ASAP](https://rssfeedasap.com/) é a forma mais fácil de encontrar o feed, normalmente você teria que conseguir o ID do canal na URL e colocar `videos.xml`.

#### GitHub
O GitHub disponibiliza alguns feeds para repositórios, entre eles `commits`, `releases` e `issues`. No repositório do [PrismLauncher](https://github.com/PrismLauncher/PrismLauncher), coloque `/commit.atom` (ou releases, etc.) no final da URL: `https://github.com/PrismLauncher/PrismLauncher/releases.atom`.

#### Bluesky
Bluesky recentemente habilitou feeds RSS para os perfis na rede social, basta colocar `/rss` ao final da URL do perfil: `https://bsky.app/profile/riiku.fun/rss`

### Aplicativos

#### Web
- Miniflux
- Inoreader
- Feedly
#### Windows
- RSSGuard
- FluentReader
#### Linux
- RSSGuard
- Newsboat (terminal)
- Newsflash
#### Android
- ReadYou
- FeedMe
#### iOS
- NetNewsWire


[^1]: https://kinsta.com/pt/wordpress-quota-mercado/
