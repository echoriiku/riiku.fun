+++
title = 'RSS é incrível, você só não sabe disso ainda'
date = 2025-03-16T00:07:55-03:00
draft = false
+++
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

## Anime & Manga Blogs 🇯🇵

- [Anime and Manga Studies](https://www.animemangastudies.com/feed/) ([feed](https://www.animemangastudies.com/feed/))
- [Full Frontal](https://fullfrontal.moe/feed/) ([feed](https://fullfrontal.moe/feed/))
- [Sakuga Blog](https://blog.sakugabooru.com/feed/) ([feed](https://blog.sakugabooru.com/feed/))
- [SatchiiKoma](https://satchiikoma.wordpress.com/feed/) ([feed](https://satchiikoma.wordpress.com/feed/))
- [ZIMMERIT](https://www.zimmerit.moe/feed/) ([feed](https://www.zimmerit.moe/feed/))

## Daily News 📰

- [404 Media](https://www.404media.co/rss/) ([feed](https://www.404media.co/rss/))
- [AlternativeTo News](https://feed.alternativeto.net/news/all/) ([feed](https://feed.alternativeto.net/news/all/))

## Developer Activity 💾

- [Miniflux Commits](https://github.com/miniflux/v2/commits.atom) ([feed](https://github.com/miniflux/v2/commits.atom))

## Gaming Blogs🕹️

- [Buried Treasure](https://buried-treasure.org/feed/) ([feed](https://buried-treasure.org/feed/))
- [CD-ROM Journal](http://cdrom.ca/feed.xml) ([feed](http://cdrom.ca/feed.xml))
- [Ephemeral Enigmas](https://ephemeralenigmascom.wordpress.com/feed/) ([feed](https://ephemeralenigmascom.wordpress.com/feed/))
- [Grand Text Auto](https://grandtextauto.soe.ucsc.edu/feed/) ([feed](https://grandtextauto.soe.ucsc.edu/feed/))
- [Hardcore Gaming 101](http://www.hardcoregaming101.net/feed/) ([feed](http://www.hardcoregaming101.net/feed/))
- [Kimimi The Game-Eating She-Monster](https://kimimithegameeatingshemonster.com/feed/) ([feed](https://kimimithegameeatingshemonster.com/feed/))
- [Painted Pixels](https://paintedpixelsblog.wordpress.com/feed/) ([feed](https://paintedpixelsblog.wordpress.com/feed/))
- [Pixel Poppers](https://pixelpoppers.com/index.xml) ([feed](https://pixelpoppers.com/index.xml))
- [Playthepast](https://www.playthepast.org/?feed=rss2) ([feed](https://www.playthepast.org/?feed=rss2))
- [Simonschreibt.](https://simonschreibt.de/feed/) ([feed](https://simonschreibt.de/feed/))
- [The Digital Antiquarian](https://www.filfre.net/feed/) ([feed](https://www.filfre.net/feed/))
- [TheFrugalGamer.Net Updates Log](https://www.thefrugalgamer.net/rss.xml) ([feed](https://www.thefrugalgamer.net/rss.xml))
- [Toomanywires](https://www.blogger.com/feeds/416041531001318874/posts/default) ([feed](https://www.blogger.com/feeds/416041531001318874/posts/default))
- [Whirlitzer of Wisdom](https://whirlitzer-of-wisdom.blogspot.com/feeds/posts/default) ([feed](https://whirlitzer-of-wisdom.blogspot.com/feeds/posts/default))

## Mags & Articles 📚

- [Yokogao Magazine │ Japanese Culture Magazine](https://www.yokogaomag.com/) ([feed](https://rss.diffbot.com/atom?url=https://www.yokogaomag.com/))
- [Asterisk](https://asteriskmag.com/feed) ([feed](https://asteriskmag.com/feed))
- [Blue Labyrinths](https://bluelabyrinths.com/feed/) ([feed](https://bluelabyrinths.com/feed/))
- [Coda Story](https://www.codastory.com/feed/) ([feed](https://www.codastory.com/feed/))
- [Epoché Magazine](https://epochemagazine.org/feed/) ([feed](https://epochemagazine.org/feed/))
- [Hazlitt](https://hazlitt.net/rss.xml) ([feed](https://hazlitt.net/rss.xml))
- [NOEMA](https://www.noemamag.com/?feed=noemarss) ([feed](https://www.noemamag.com/?feed=noemarss))
- [The Atavist Magazine](https://magazine.atavist.com/feed/) ([feed](https://magazine.atavist.com/feed/))

## Miscellaneous 🌈

- [Have I Been Pwned](https://haveibeenpwned.com) ([feed](http://feeds.feedburner.com/HaveIBeenPwnedLatestBreaches?ref=troyhunt.com))
- [Obsidian Journey](https://obsidianjourney.com/) ([feed](https://obsidianjourney.com/index.xml))
- [ooh.directory recently added blogs](https://ooh.directory/feeds/recently-added.xml) ([feed](https://ooh.directory/feeds/recently-added.xml))

## Open Source & Linux News 🐧

- [Fedora Magazine](https://fedoramagazine.org/) ([feed](https://fedoramagazine.org/feed/))
- [KDE Blogs](https://blogs.kde.org/index.xml) ([feed](https://blogs.kde.org/index.xml))
- [This Week in GNOME](https://thisweek.gnome.org/index.xml) ([feed](https://thisweek.gnome.org/index.xml))
- [This Week in KDE](https://pointieststick.com/category/this-week-in-kde/feed/) ([feed](https://pointieststick.com/category/this-week-in-kde/feed/))

## Personal Blogs 📝

- [82MHz](https://82mhz.net/) ([feed](https://82mhz.net/index.xml))
- [A Collection of Unmitigated Pedantry](https://acoup.blog/feed/) ([feed](https://acoup.blog/feed/))
- [Analog Office](https://analogoffice.net/feed.xml) ([feed](https://analogoffice.net/feed.xml))
- [AndreGarzia.com](https://andregarzia.com/feeds/all.atom.xml) ([feed](https://andregarzia.com/feeds/all.atom.xml))
- [ASCII by Jason Scott](http://ascii.textfiles.com/feed) ([feed](http://ascii.textfiles.com/feed))
- [Bacardi55's Web Cave](https://bacardi55.io/posts/) ([feed](https://bacardi55.io/posts/index.xml))
- [Bobulate](https://bobulate.com/feed/) ([feed](https://bobulate.com/feed/))
- [Cassidy Williams](https://cassidoo.co/) ([feed](https://cassidoo.co/rss.xml))
- [Cross Dominant](https://conoroneill.net/) ([feed](https://conoroneill.net/index.xml))
- [datagubbe](https://www.datagubbe.se/atom.xml) ([feed](https://www.datagubbe.se/atom.xml))
- [Daudix - Progressive Enhancement](https://daudix.one/blog/) ([feed](https://daudix.one/blog/atom.xml))
- [Dhole Moments](https://soatok.blog/feed/) ([feed](https://soatok.blog/feed/))
- [Eccentric Computing](https://ecc-comp.blogspot.com/feeds/posts/default) ([feed](https://ecc-comp.blogspot.com/feeds/posts/default))
- [Ed Leeman](https://edleeman.co.uk/index.xml) ([feed](https://edleeman.co.uk/index.xml))
- [Erin Kissane's small internet website](https://erinkissane.com/feed.rss) ([feed](https://erinkissane.com/feed.rss))
- [Fabien Sanglard](https://fabiensanglard.net/rss.xml) ([feed](https://fabiensanglard.net/rss.xml))
- [From Earth to the Stars](https://fromearthtothestars.com/feed/) ([feed](https://fromearthtothestars.com/feed/))
- [Growing Up Transgender](https://growinguptransgender.com/feed/) ([feed](https://growinguptransgender.com/feed/))
- [Hi there! on poor.dev](https://poor.dev/index.xml) ([feed](https://poor.dev/index.xml))
- [Interplay of Light](https://interplayoflight.wordpress.com/feed/) ([feed](https://interplayoflight.wordpress.com/feed/))
- [Jim Nielsen’s Blog](https://blog.jim-nielsen.com/feed.xml) ([feed](https://blog.jim-nielsen.com/feed.xml))
- [Josh Collinsworth](https://joshcollinsworth.com/api/rss.xml) ([feed](https://joshcollinsworth.com/api/rss.xml))
- [Juha-Matti Santala - Community Builder. Dreamer. Adventurer.](https://hamatti.org/feed/feed.xml) ([feed](https://hamatti.org/feed/feed.xml))
- [Luca Marx](https://lucamarx.com/blog/rss.xml) ([feed](https://lucamarx.com/blog/rss.xml))
- [maia blog](https://maia.crimew.gay/feed.xml) ([feed](https://maia.crimew.gay/feed.xml))
- [Manual do Usuário](https://manualdousuario.net/feed/) ([feed](https://manualdousuario.net/feed/))
- [Marius Masalar](https://marius.ink/feed.atom) ([feed](https://marius.ink/feed.atom))
- [Max Glenister](https://blog.omgmog.net/feed.xml) ([feed](https://blog.omgmog.net/feed.xml))
- [maya.land](https://maya.land/feed.xml) ([feed](https://maya.land/feed.xml))
- [Mike Blumenkrantz](https://www.supergoodcode.com/feed.xml) ([feed](https://www.supergoodcode.com/feed.xml))
- [Minutes to Midnight](https://minutestomidnight.co.uk) ([feed](https://minutestomidnight.co.uk/feed.xml))
- [Neil Gaiman's Journal](https://journal.neilgaiman.com/feeds/posts/default) ([feed](https://journal.neilgaiman.com/feeds/posts/default))
- [Nickdiego Blog](http://nickdiego.dev/blog/) ([feed](https://nickdiego.dev/blog/index.xml))
- [Nicole Express](https://nicole.express/feed.xml) ([feed](https://nicole.express/feed.xml))
- [On Life and Lisp](https://rosenzweig.io/feed.xml) ([feed](https://rosenzweig.io/feed.xml))
- [Practical betterments](https://practicalbetterments.com/feed.xml) ([feed](https://practicalbetterments.com/feed.xml))
- [Querido Clássico](https://www.queridoclassico.com/feeds/posts/default) ([feed](https://www.queridoclassico.com/feeds/posts/default))
- [ResoluteReader](https://resolutereader.blogspot.com/feeds/posts/default) ([feed](https://resolutereader.blogspot.com/feeds/posts/default))
- [Roar of the Days](https://so1o.xyz/blog/) ([feed](https://so1o.xyz/feed.xml))
- [Robb Knight • Posts • Atom Feed](https://rknight.me/subscribe/posts/atom.xml) ([feed](https://rknight.me/subscribe/posts/atom.xml))
- [Rubenerd](https://rubenerd.com/feed/) ([feed](https://rubenerd.com/feed/))
- [sdomi's weblog](https://sdomi.pl/weblog/atom/) ([feed](https://sdomi.pl/weblog/atom/))
- [slatecave.net](https://slatecave.net/atom.xml) ([feed](https://slatecave.net/atom.xml))
- [Sympolymathesy, by Chris Krycho](https://v5.chriskrycho.com/feed.xml) ([feed](https://v5.chriskrycho.com/feed.xml))
- [The Ethically-Trained Programmer](https://blog.carlana.net/index.xml) ([feed](https://blog.carlana.net/index.xml))
- [The OSS History Newsletter](https://osshistory.org/feed) ([feed](https://osshistory.org/feed))
- [Thomas Stringer](https://trstringer.com/feed.xml) ([feed](https://trstringer.com/feed.xml))
- [Uncharted Worlds](https://www.uncharted-worlds.org/blog/feed/) ([feed](https://www.uncharted-worlds.org/blog/feed/))
- [VADOSWARE](https://vadosware.io/index.xml) ([feed](https://vadosware.io/index.xml))
- [violeta | ceci blog](https://cheshireviolet.github.io/) ([feed](https://cheshireviolet.github.io/index.xml))
- [Vlad Zahorodnii's Blog](https://blog.vladzahorodnii.com/feed/) ([feed](https://blog.vladzahorodnii.com/feed/))

