+++
title = 'RSS é incrível, você só não sabe disso ainda'
date = 2025-03-16T00:07:55-03:00
draft = false
tags = ['tutorial']
+++

# RSS é incrível, você só não sabe disso ainda

Outro dia, um post meu no Bluesky ganhou bastante atenção, felizmente por um bom motivo. O post em questão falava sobre RSS, feed readers e em como eles deveriam ressurgir.

Essa postagem me fez pensar nas várias possibilidades que RSS tem a oferecer. Por isso, vou aproveitar e mostrar algumas das várias formas de usar RSS e quem sabe isso não desperta um novo interesse em você?

## YouTube

Por incrível que pareça, poucos sabem que é possível seguir canais do YouTube usando RSS. Desde que a Google matou a possibilidade de seguir canais e receber atualizações de forma cronológica, seguir canais via RSS se tornou uma opção ainda mais relevante.

Usando RSS, você pode seguir qualquer canal ou playlist sem se preocupar com algoritmo ditando o que você deve assistir. Basta colar a URL do canal em um leitor de RSS que ele deverá conseguir extrair o feed da página.

Para isso, vamos utilizar uma ferramenta para descobrir feeds RSS nos sites que iremos visitar. Existem várias, mas a minha preferida é o [Get RSS Feed](https://getrssfeed.com/), já testei várias e essa foi a melhor até hoje.

![](https://i.ibb.co/Qjqn9SLD/coisas-legais-que-voc-pode-fazer-com-rss-1742075676391.webp)

Usando o RSS Feed ASAP, basta colar a URL do canal do YouTube (ou a URL da playlist) que ele irá extrair a URL do Feed RSS pra você seguir no seu leitor RSS de preferência.

Um dos meus canais preferidos é o PPF, ele faz covers de músicas de video-games, só que infelizmente ele demora muito entre uma postagem e outra, por isso, eu sempre perdia quando um vídeo novo era postado.

![](https://i.ibb.co/mrkLtvgN/coisas-legais-que-voc-pode-fazer-com-rss-1742076166398.webp)

Com o [Get RSS Feed](https://getrssfeed.com/), eu consigo essa URL: `https://www.youtube.com/feeds/videos.xml?channel_id=UCohllq0Pk5lQuuNANabHKcg`, que, apesar de ficar escondida, é oficialmente disponibilizada pelo YouTube. Agora você nunca mais vai perder uma postagem do seu canal preferido.

## Bluesky / Mastodon

Ao contrário da rede social do megalomaníaco bilionário, Bluesky (e o Mastodon, que por sinal implementou isso primeiro), disponibilizam feed RSS de todos os perfis públicos.

Diferente do YouTube, é super fácil descobrir a URL do Feed de um perfil, basta copiar a URL do perfil e adicionar `/rss` no final da URL!

![](https://i.ibb.co/Y7G01tj9/coisas-legais-que-voc-pode-fazer-com-rss-1742077389834.webp)

Pronto, agora você nunca mais vai perder a postagem daquele perfil que você adora!

## Steam

Que tal ficar sempre atualizado com as novidades dos seus jogos preferidos? Saber exatamente quando aquela DLC saiu ou quando aquele jogo que você adora mas não recebe atualizações há meses finalmente recebe conteúdos novos? Com RSS isso é possível!

O Steam infelizmente não deixa tão claro que é possível fazer isso, mas depois que você descobre, é bem fácil de usar.

![](https://i.ibb.co/5WZPkdfc/coisas-legais-que-voc-pode-fazer-com-rss-1742080357887.webp)

Primeiro precisamos do `APP ID` do jogo que você quer seguir. Ele é encontrado na URL da página da loja do jogo no Steam. Por exemplo, essa é a URL da página do jogo Hollow Knight: <https://store.steampowered.com/app/367520/Hollow_Knight/>. O `APP ID` de Hollow Knight é 367520. Com esse número guardado, vamos adicioná-lo à URL de Feeds que o Steam disponibiliza: `https://store.steampowered.com/feeds/news/app/[APPID DO JOGO]`. Basta colocar o `APP ID` do jogo ao final da URL que você vai ter acesso ao feed de atualizações diretamente no seu leitor RSS.

## E isso é só o começo

Tem MUITO mais coisa que você pode seguir usando RSS, desde releases a commits no GitHub, sites de notícias (os bons sempre têm RSS), blogs, as possibilidades são enormes!

Além do mais, todas as suas inscrições podem ser exportadas (ou importadas) usando um arquivo `.opml`.Esse arquivo é aceito por todos os leitores de RSS e você pode facilmente migrar seus Feeds de um serviço/app para outro. Procure pela opção exportar/importar no seu leitor que você vai achar onde usar arquivo `.opml`.

E já que não dá pra seguir um Feed sem um app dedicado, aqui vão algumas recomendações dividas por plataforma:

- Web: [Feedly](https://feedly.com/), [Miniflux](https://miniflux.app/), https://www.inoreader.com/
- Windows: [RSSGuard](https://github.com/martinrotter/rssguard) e [FluentReader](https://github.com/yang991178/fluent-reader)
- iOS & MacOS: [NetNewsWire](https://netnewswire.com/)
- Android: [CapyReader](https://github.com/jocmp/capyreader) e [ReadYou](https://github.com/Ashinch/ReadYou)
- Linux: [NewsFlash](https://gitlab.com/news-flash/news_flash_gtk), [Akregator](https://kontact.kde.org/components/akregator/) e [RSSGuard](https://github.com/martinrotter/rssguard)

Depois da lista de apps, nada melhor que uma lista de feeds pra você seguir, esses são alguns dos que eu sigo no meu leitor de RSS, sinta-se à vontade pra seguir alguns e aproveitar a liberdade de um feed sem algoritmos que você tem total controle sobre o que aparece nele.

---

## Personal Blogs 📝

- [82MHz](https://82mhz.net/)
- [A Collection of Unmitigated Pedantry](https://acoup.blog/)
- [Analog Office](https://analogoffice.net/)
- [AndreGarzia.com](https://andregarzia.com/)
- [ASCII by Jason Scott](http://ascii.textfiles.com/)
- [Bacardi55's Web Cave](https://bacardi55.io/posts/)
- [Bobulate](https://bobulate.com/)
- [Cassidy Williams](https://cassidoo.co/)
- [Cross Dominant](https://conoroneill.net/)
- [datagubbe](https://www.datagubbe.se/)
- [Daudix - Progressive Enhancement](https://daudix.one/blog/)
- [Dhole Moments](https://soatok.blog/)
- [Eccentric Computing](https://ecc-comp.blogspot.com/)
- [Ed Leeman](https://edleeman.co.uk/)
- [Erin Kissane's small internet website](https://erinkissane.com/)
- [Fabien Sanglard](https://fabiensanglard.net/)
- [From Earth to the Stars](https://fromearthtothestars.com/)
- [Growing Up Transgender](https://growinguptransgender.com/)
- [Hi there! on poor.dev](https://poor.dev/)
- [Interplay of Light](https://interplayoflight.wordpress.com/)
- [Jim Nielsen’s Blog](https://blog.jim-nielsen.com/)
- [Josh Collinsworth](https://joshcollinsworth.com/)
- [Juha-Matti Santala - Community Builder. Dreamer. Adventurer.](https://hamatti.org/)
- [Luca Marx](https://lucamarx.com/blog/)
- [maia blog](https://maia.crimew.gay/)
- [Manual do Usuário](https://manualdousuario.net/)
- [Marius Masalar](https://marius.ink/)
- [Max Glenister](https://blog.omgmog.net/)
- [maya.land](https://maya.land/)
- [Mike Blumenkrantz](https://www.supergoodcode.com/)
- [Minutes to Midnight](https://minutestomidnight.co.uk)
- [Neil Gaiman's Journal](https://journal.neilgaiman.com/)
- [Nickdiego Blog](http://nickdiego.dev/blog/)
- [Nicole Express](https://nicole.express/)
- [On Life and Lisp](https://rosenzweig.io/)
- [Practical betterments](https://practicalbetterments.com/)
- [Querido Clássico](https://www.queridoclassico.com/)
- [ResoluteReader](https://resolutereader.blogspot.com/)
- [Roar of the Days](https://so1o.xyz/blog/)
- [Robb Knight • Posts • Atom Feed](https://rknight.me/)
- [Rubenerd](https://rubenerd.com/)
- [sdomi's weblog](https://sdomi.pl/weblog/)
- [slatecave.net](https://slatecave.net/)
- [Sympolymathesy, by Chris Krycho](https://v5.chriskrycho.com/)
- [The Ethically-Trained Programmer](https://blog.carlana.net/)
- [The OSS History Newsletter](https://osshistory.org/)
- [Thomas Stringer](https://trstringer.com/)
- [Uncharted Worlds](https://www.uncharted-worlds.org/blog/)
- [VADOSWARE](https://vadosware.io/)
- [violeta | ceci blog](https://cheshireviolet.github.io/)
- [Vlad Zahorodnii's Blog](https://blog.vladzahorodnii.com/)

## Mags & Articles 📚

- [Yokogao Magazine │ Japanese Culture Magazine](https://www.yokogaomag.com/)
- [Asterisk](https://asteriskmag.com/)
- [Blue Labyrinths](https://bluelabyrinths.com/)
- [Coda Story](https://www.codastory.com/)
- [Epoché Magazine](https://epochemagazine.org/)
- [Hazlitt](https://hazlitt.net/)
- [NOEMA](https://www.noemamag.com/)
- [The Atavist Magazine](https://magazine.atavist.com/)

## Anime & Manga Blogs 🇯🇵

- [Anime and Manga Studies](https://www.animemangastudies.com/)
- [Full Frontal](https://fullfrontal.moe/)
- [Sakuga Blog](https://blog.sakugabooru.com/)
- [SatchiiKoma](https://satchiikoma.wordpress.com/)
- [ZIMMERIT](https://www.zimmerit.moe/)

## Daily News 📰

- [404 Media](https://www.404media.co/)
- [AlternativeTo News](https://alternativeto.net/news/all/)

## Developer Activity 💾

- [Miniflux Commits](https://github.com/miniflux/v2/commits.atom)

## Gaming Blogs🕹️

- [Buried Treasure](https://buried-treasure.org/)
- [CD-ROM Journal](http://cdrom.ca/)
- [Ephemeral Enigmas](https://ephemeralenigmascom.wordpress.com/)
- [Grand Text Auto](https://grandtextauto.soe.ucsc.edu/)
- [Hardcore Gaming 101](http://www.hardcoregaming101.net/)
- [Kimimi The Game-Eating She-Monster](https://kimimithegameeatingshemonster.com/)
- [Painted Pixels](https://paintedpixelsblog.wordpress.com/)
- [Pixel Poppers](https://pixelpoppers.com/)
- [Playthepast](https://www.playthepast.org/)
- [Simonschreibt.](https://simonschreibt.de/)
- [The Digital Antiquarian](https://www.filfre.net/)
- [TheFrugalGamer.Net Updates Log](https://www.thefrugalgamer.net/)
- [Toomanywires](https://www.blogger.com/feeds/416041531001318874/posts/default)
- [Whirlitzer of Wisdom](https://whirlitzer-of-wisdom.blogspot.com/)

## Miscellaneous 🌈

- [Have I Been Pwned](https://haveibeenpwned.com)
- [Obsidian Journey](https://obsidianjourney.com/)
- [ooh.directory recently added blogs](https://ooh.directory/)

## Open Source & Linux News 🐧

- [Fedora Magazine](https://fedoramagazine.org/)
- [KDE Blogs](https://blogs.kde.org/)
- [This Week in GNOME](https://thisweek.gnome.org/)
- [This Week in KDE](https://pointieststick.com/category/this-week-in-kde/)
