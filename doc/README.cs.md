<p align="center"><a href="https://newpipe.net"><img src="assets/new_pipe_icon_5.png" width="150"></a></p> 
<h2 align="center"><b>NewPipe</b></h2>
<h4 align="center">A libre lightweight streaming front-end for Android.</h4>

<p align="center"><a href="https://f-droid.org/packages/org.schabi.newpipe/"><img src="https://fdroid.gitlab.io/artwork/badge/get-it-on-en.svg" alt="Get it on F-Droid" width=206/></a></p>

<p align="center">
<a href="https://github.com/TeamNewPipe/NewPipe/releases" alt="GitHub NewPipe releases"><img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe.svg" ></a>
<a href="https://github.com/TeamNewPipe/NewPipe-nightly/releases" alt="GitHub NewPipe nightly releases"><img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe-nightly.svg?labelColor=purple&label=dev%20nightly"></a>
<a href="https://www.gnu.org/licenses/gpl-3.0" alt="License: GPLv3"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg"></a>
<a href="https://github.com/TeamNewPipe/NewPipe/actions" alt="Build Status"><img src="https://github.com/TeamNewPipe/NewPipe/actions/workflows/ci.yml/badge.svg?branch=dev&event=push"></a>
<a href="https://hosted.weblate.org/engage/newpipe/" alt="Translation Status"><img src="https://hosted.weblate.org/widgets/newpipe/-/svg-badge.svg"></a>
</p>

<p align="center">
<a href="https://web.libera.chat/#newpipe" alt="IRC channel: #newpipe"><img src="https://img.shields.io/badge/IRC%20chat-%23newpipe-brightgreen.svg"></a>
<a href="https://matrix.to/#/#newpipe:matrix.newpipe-ev.de" alt="Matrix channel: #newpipe"><img src="https://img.shields.io/badge/Matrix%20chat-%23newpipe-blue"></a>
</p>

<hr>
<p align="center"><a href="#screenshots">Screenshots</a> &bull; <a href="#supported-services">Supported Services</a> &bull; <a href="#description">Description</a> &bull; <a href="#features">Features</a> &bull; <a href="#installation-and-updates">Installation and updates</a> &bull; <a href="#contribution">Contribution</a> &bull; <a href="#donate">Donate</a> &bull; <a href="#license">License</a></p>
<p align="center"><a href="https://newpipe.net">Website</a> &bull; <a href="https://newpipe.net/blog/">Blog</a> &bull; <a href="https://newpipe.net/FAQ/">FAQ</a> &bull; <a href="https://newpipe.net/press/">Press</a></p>
<hr>

*Přečtěte si tento dokument v jiných jazycích: [Deutsch](doc/README.de.md),
[English](README.md), [Español](doc/README.es.md), [Français](doc/README.fr.md),
[हिन्दी](doc/README.hi.md), [Italiano](doc/README.it.md),
[한국어](doc/README.ko.md), [Português Brasil](doc/README.pt_BR.md),
[Polski](doc/README.pl.md), [ਪੰਜਾਬੀ ](doc/README.pa.md),
[日本語](doc/README.ja.md), [Română](doc/README.ro.md),
[Soomaali](doc/README.so.md), [Türkçe](doc/README.tr.md),
[正體中文](doc/README.zh_TW.md), [অসমীয়া](doc/README.asm.md),
[Српски](doc/README.sr.md), [العربية](README.ar.md)*

> [!warning]\
> <b>TATO APLIKACE JE VE VERZI BETA, MOHOU SE OBJEVIT CHYBY. POKUD SE TAK STANE,
> OTEVŘETE SI PROBLÉM V NAŠEM REPOZITÁŘI VYPLNĚNÍM ŠABLONY PROBLÉMU.</b>
> 
> <b>UMÍSTĚNÍ APLIKACE NEWPIPE NEBO JAKÉHOKOLI JEJÍHO FORKU DO OBCHODU GOOGLE
> PLAY PORUŠUJE JEJICH PODMÍNKY.</b>
> 
> <b>„NewPipe“ JE REGISTROVANÁ SLOVNÍ ZNAČKA, NA KTEROU SE VZTAHUJE [JEJÍ
> POLITIKA OCHRANNÝCH ZNÁMEK](https://newpipe-ev.de/policy/trademark/).
> PORUŠUJÍCÍ POUŽITÍ NEBUDE TOLEROVÁNO.</b>

## Snímky obrazovky

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/00.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/00.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/01.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/01.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/02.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/02.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/03.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/03.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/04.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/04.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/05.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/05.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/06.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/06.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/07.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/07.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/08.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/08.png)
<br/><br/>\
[<img src="fastlane/metadata/android/en-US/images/tenInchScreenshots/09.png" width=405>](fastlane/metadata/android/en-US/images/tenInchScreenshots/09.png)
[<img src="fastlane/metadata/android/en-US/images/tenInchScreenshots/10.png" width=405>](fastlane/metadata/android/en-US/images/tenInchScreenshots/10.png)

### Podporované služby

NewPipe v současné době podporuje tyto služby:

<!-- We link to the service websites separately to avoid people accidentally opening a website they didn't want to. -->
* YouTube ([web](https://www.youtube.com/)) a YouTube Music
  ([web](https://music.youtube.com/))
  ([wiki](https://en.wikipedia.org/wiki/YouTube))
* PeerTube ([web](https://joinpeertube.org/)) a všechny jeho instance (pro více
  informací si otevřete web!) ([wiki](https://en.wikipedia.org/wiki/PeerTube))
* Bandcamp ([web](https://bandcamp.com/))
  ([wiki](https://en.wikipedia.org/wiki/Bandcamp))
* SoundCloud ([web](https://soundcloud.com/))
  ([wiki](https://en.wikipedia.org/wiki/SoundCloud))
* media.ccc.de ([web](https://media.ccc.de/))
  ([wiki](https://en.wikipedia.org/wiki/Chaos_Computer_Club))

Jak vidíte, NewPipe podporuje celou řadu video a audio služeb. Ačkoli to všechno
začalo s YouTube, v průběhu let ostatní uživatelé přidali další služby, díky
čemuž je NewPipe čím dál tím všestrannější!

Částečně kvůli okolnostem a částečně díky své popularitě je z těchto služeb
nejlépe podporován YouTube. Pokud některou z těchto dalších služeb používáte
nebo ji znáte, pomozte nám prosím zlepšit její podporu! Hledáme správce pro
SoundCloud a PeerTube.

Pokud máte v plánu přidat novou službu, nejprve nás prosím kontaktujte! Naše
[dokumentace](https://teamnewpipe.github.io/documentation/) poskytuje více
informací o způsobu, jakým lze novou službu přidat do aplikace a [Extraktoru
NewPipe](https://github.com/TeamNewPipe/NewPipeExtractor).

## Popis

NewPipe funguje tak, že načítá potřebná data z oficiálního API (např. PeerTube)
služby, kterou právě používáte. Pokud je oficiální API pro naše účely omezené
(např. YouTube) nebo je proprietární, aplikace místo toho analyzuje webovou
stránku nebo využívá interní API. To znamená, že k používání NewPipe
nepotřebujete účet u žádné služby.

Jelikož se navíc jedná o bezplatný software s otevřeným zdrojovým kódem,
nepoužívá ani aplikace, ani extraktor žádné proprietární knihovny či frameworky,
jako jsou například Služby Google Play. To znamená, že můžete NewPipe používat
na zařízeních nebo s vlastními ROM, na kterých nejsou nainstalovány aplikace
Google.

### Funkce

* Sledování videí v rozlišeních až do 4K
* Poslech zvuku na pozadí, kdy se načte pouze zvuková stopa pro uspoření dat
* Režim obrazu v obraze (plovoucí přehrávač)
* Sledování živých přenosů
* Zobrazení/skrytí titulků
* Hledání videí a zvuku (na YouTube můžete také určit jazyk obsahu)
* Vkládání videí do fronty (a volitelné uložení do lokálních playlistů)
* Zobrazení/skrytí obecných informací o videích (např. popis a štítky)
* Zobrazení/skrytí dalších/souvisejících videí
* Zobrazení/skrytí komentářů
* Hledání videí, zvuku, kanálů, playlistů a alb
* Procházení videí a zvuku v kanálu
* Odebírání kanálů (bez přihlášení k účtu!)
* Získávání oznámení o nových videí u kanálů, které odebíráte
* Vytváření a úprava skupin kanálů (pro jednodušší procházení a správu)
* Procházení seznamů videí generovaných ze skupin vašich kanálů
* Zobrazení a vyhledávání v historii sledování
* Vyhledávání a sledování playlistů (vzdálených, což znamená, že jsou stahovány
  ze služby, kterou procházíte)
* Vytváření a úprava lokálních playlistů (vytvořené a uložené v aplikaci a
  nemají nic společného s jakoukoli službou)
* Stahování videí/zvuku/titulků (i skrytých)
* Otevření v Kodi
* Sledování/blokování obsahu s věkovým omezením

<!-- Hidden span to keep old links compatible. You should remove this span if you're translating the README into another language.-->
<span id="updates"></span>

## Instalace a aktualizace
NewPipe můžete nainstalovat pomocí jednoho z následujících způsobů:
 1. Přidejte si náš vlastní repozitář do F-Droidu a nainstalujte si jej odsud.
    Instrukce naleznete zde:
    https://newpipe.net/FAQ/tutorials/install-add-fdroid-repo/
 2. Stáhněte si soubor APK z [vydání na
    GitHubu](https://github.com/TeamNewPipe/NewPipe/releases), [porovnejte
    podpisový klíč](#apk-info) a nainstalujte jej.
 3. Aktualizujte aplikaci přes F-Droid. Toto je nejpomalejší způsob získávání
    aktualizací, jelikož F-Droid musí nejprve detekovat změny, sestavit soubor
    APK, podepsat jej a až poté odeslat aktualizaci uživatelům.
 4. Sami si sestavte ladicí soubor APK. Toto je nejrychlejší způsob, jak dostat
    nové funkce na vaše zařízení, je ale zároveň mnohem komplikovanější,
    doporučujeme tedy využít jednu z ostatních metod.
 5. Pokud vás zajímá konkrétní funkce nebo oprava chyby obsažená v žádosti o
    sloučení (Pull Request) v tomto repozitáři, můžete si její soubor APK
    stáhnout přímo z této žádosti. Pokyny najdete v popisu žádosti. Výhodou
    souborů APK vázaných na konkrétní žádosti je to, že se instalují souběžně s
    oficiální aplikací, takže se nemusíte obávat ztráty dat ani toho, že byste
    něco pokazili.

Většině uživatelů doporučujeme způsob 1. Soubory APK nainstalované způsobem 1
nebo 2 jsou vzájemně kompatibilní (to znamená, že pokud jste nainstalovali
NewPipe způsobem 1 nebo 2, můžete NewPipe aktualizovat i druhým způsobem), ale
nejsou kompatibilní s těmi, které byly nainstalovány způsobem 3. Důvodem je, že
pro způsoby 1 a 2 se používá stejný podpisový klíč (náš), zatímco pro způsob 3
se používá jiný podpisový klíč (F-Droid). Při sestavení ladicího souboru APK
způsobem 4 se klíč zcela vynechává. Podpisové klíče pomáhají zajistit, aby
uživatel nebyl podveden k instalaci škodlivé aktualizace aplikace. Při použití
způsobu 5 je každý soubor APK podepsán jiným náhodným klíčem poskytnutým službou
GitHub Actions, takže jej ani nelze aktualizovat. Pokaždé, když budete chtít
použít nový soubor APK, budete muset zálohovat a obnovit data aplikace.

Mezitím, pokud z nějakého důvodu chcete přepnout mezi zdroji (např. je rozbitá
základní funkcionalita NewPipe a F-Droid zatím nemá poslední aktualizaci),
doporučujeme provést následující:
1. Zálohujte si svá data skrze Nastavení > Záloha a obnovení > Exportovat
   databázi, abyste si ponechali svou historii, odběry a playlisty
2. Odinstalujte NewPipe
3. Stáhněte si soubor APK z nového zdroje a nainstalujte si ho
4. Importujte si data z kroku 1 skrze Nastavení > Záloha a obnovení > Importovat
   databázi

> [!Note] Při importu databáze do oficiální aplikace se ujistěte, že se jedná o
> tu, kterou jste exportovali _z_ oficiální aplikace. Pokud importujete databázi
> exportovanou z jiné než oficiální aplikace, může aplikaci rozbít. Taková akce
> je nepodporovaná a měli byste ji provést pouze, pokud jste si naprosto jistí
> tím, co děláte.

### Informace o souborech APK

Toto je SHA otisk podpisového klíče NewPipe pro ověření stažených souborů APK,
které jsou podepsané námi. Otisk je dostupný také na [webu
NewPipe](https://newpipe.net#download). Toto se týká metody 2.
```
CB:84:06:9B:D6:81:16:BA:FA:E5:EE:4E:E5:B0:8A:56:7A:A6:D8:98:40:4E:7C:B1:2F:9E:75:6D:F5:CF:5C:AB
```

## Přispívání
Ať už máte nápady, překlady, designové změny, pročištění kódu nebo i velké změny
v něm, pomoc je vždy vítána. Aplikace se zlepšuje každým přispěním, nezávisle na
jeho velikosti! Pokud se chcete zapojit, přečtěte si naše [informace o
přispívání](.github/CONTRIBUTING.md).

<a href="https://hosted.weblate.org/engage/newpipe/">
<img src="https://hosted.weblate.org/widgets/newpipe/-/287x66-grey.png" alt="Translation status" />
</a>

## Podpořte projekt
Pokud se vám NewPipe líbí, budeme rádi za váš dar. Preferujeme platformu
Liberapay, protože je open-source a nezisková. Pro více informací o darování
projektu NewPipe navštivte náš [web](https://newpipe.net/donate).

<table>
  <tr>
    <td><a href="https://liberapay.com/TeamNewPipe/"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/Liberapay_logo_v2_white-on-yellow.svg" alt="Liberapay" width="80px" ></a></td>
    <td><a href="https://liberapay.com/TeamNewPipe/"><img src="assets/liberapay_qr_code.png" alt="Visit NewPipe at liberapay.com" width="100px"></a></td>
    <td><a href="https://liberapay.com/TeamNewPipe/donate"><img src="assets/liberapay_donate_button.svg" alt="Donate via Liberapay" height="35px"></a></td>
  </tr>
</table>

## Ochrana soukromí

Cílem projektu NewPipe je zajistit soukromé a anonymní prostředí při využívání
webových mediálních služeb. Aplikace proto bez vašeho souhlasu neshromažďuje
žádná data. Zásady ochrany osobních údajů NewPipe podrobně vysvětlují, jaká data
se odesílají a ukládají, když odešlete hlášení o chybě nebo zanecháte komentář
na našem blogu. Tento dokument najdete
[zde](https://newpipe.net/legal/privacy/).

## Licence
[![GNU GPLv3
Image](https://www.gnu.org/graphics/gplv3-127x51.png)](https://www.gnu.org/licenses/gpl-3.0.en.html)

NewPipe je svobodný software: Můžete jej svobodně používat, studovat, sdílet a
vylepšovat. Konkrétně jej můžete redistribuovat a/nebo upravovat pod podmínkami
licence [GNU General Public License](https://www.gnu.org/licenses/gpl.html)
zveřejněné nadací Free Software Foundation, buď ve verzi 3, nebo (dle vašeho
uvážení) v jakékoli pozdější verzi.
