+++
title = 'Self-Hosting'
date = 2025-02-15T19:59:01-03:00
draft = false
+++

Em 2025, decidi mudar um pouco as coisas. Pra começar, finalmente entendi que não preciso começar sempre pelo método mais completo (que acaba sendo mais difícil), não tem nada de errado em dar pequenos passos pra depois correr.

Ano passado, em 2024, comecei a fazer 'self-hosting' de alguns aplicativos, self-hosting entre aspas pois pra alguns só é self-hosting de verdade quando você faz tudo em casa, com seu próprio hardware. Algo que, infelizmente, não é o meu caso, considerando os desafios de manter um computador ligado 24 horas por dia, 7 dias por semana no Brasil. Por isso, optei por uma VPS, um servidor Linux remoto.

Como eu sabia pouco sobre self-hosting, comecei usando um aplicativo chamado Caprover, que basicamente gerenciava tudo para mim, desde a instalação de aplicativos com um clique até certificados para que meu site pudesse usar HTTPS. Isso tudo era uma mão na roda, uma pá de aplicativos pra só clicar e rodar. Só que, como qualquer programa, algumas coisas nem sempre funcionam como esperado. Nessas horas, eu precisava colocar a mão na massa, abrir o terminal da VPS e tentar descobrir como fazer o que eu precisava, seja para resolver um problema ou para realizar algo que eu queria com um aplicativo (como quando precisei fazer backup de um banco de dados. Eu nunca tinha feito isso antes, mas aprendi a acessar um container Docker em execução, fazer o dump do banco de dados e copiar para fora do container!).

## Novo ano, nova VPS

Com a virada do ano, os preços da VPS que estava usando aumentaram, o que me fez buscar por outras alternativas. Aproveitei a oportunidade para começar tudo do zero, fazendo o máximo possível manualmente. Para isso, instalei o Debian (ao invés do Ubuntu da antiga VPS), fiz a configuração básica do Docker, instalei o [Caddy](https://caddyserver.com/) para usar como proxy reverso e criei uma série de pastas para cada aplicativo, cada uma com seu arquivo docker-compose.yaml dentro, deixando tudo organizado.

Atualmente, tenho 23 containers em execução e 16 serviços. Os meus mais utilizados são:

- [Miniflux](<https://miniflux.app/>), um leitor de RSS minimalista que é simplesmente delicioso de usar.

- [RSSHub](<https://docs.rsshub.app/>), um serviço que basicamente cria feeds de RSS de ~quase~ qualquer coisa, complementa o Miniflux.

- [Readeck](<https://readeck.org/en/>), um read-it-later, onde posso salvar os artigos/links mais legais que chegam pelo Miniflux pra ler depois (os poucos que não leio diretamente no Miniflux)

- [SearXNG](<https://docs.searxng.org/>), literalmente um mecanismo de busca, só que ‘meu’!

É muito bom ter total controle sobre um serviço que você pode acessar de qualquer lugar, e que não é controlado por uma grande empresa de tecnologia. Todos esses serviços/aplicativos que tenho na minha VPS são de código aberto, gratuitos e contam com a colaboração da comunidade para o desenvolvimento.

Apesar de tudo isso, acho que self-hosting é algo que todo que gosta um pouco de computadores deveria tentar, na grande maioria das vezes você nem precisa de um servidor remoto, tem inúmeros apps que funcionam localmente usando docker, fora que é uma excelente oportunidade pra aprender mais sobre como esses serviços funcionam.

Coisas que aprendi nessa pequena jornada:

- Docker

    - Containers

    - Volumes

    - Networks

- Reverse Proxy

- SSH e SSH-Keys

Antes não conseguiria sem a ajuda do Caprover, hoje já consigo usando Caddy, no futuro, quero aprender a usar Traefik. Veremos o que 2025 tem pela frente.


Se tiverem algum comentário, dúvida ou sugestão, me mande um [e-mail](<mailto:ricardoars@tuta.io>)!
