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

*Lea este documento noutros idiomas: [Deutsch](doc/README.de.md),
[English](README.md), [Español](doc/README.es.md), [Français](doc/README.fr.md),
[हिन्दी](doc/README.hi.md), [Italiano](doc/README.it.md),
[한국어](doc/README.ko.md), [Português Brasil](doc/README.pt_BR.md),
[Polski](doc/README.pl.md), [ਪੰਜਾਬੀ ](doc/README.pa.md),
[日本語](doc/README.ja.md), [Română](doc/README.ro.md),
[Soomaali](doc/README.so.md), [Türkçe](doc/README.tr.md),
[正體中文](doc/README.zh_TW.md), [অসমীয়া](doc/README.asm.md),
[Српски](doc/README.sr.md), [العربية](README.ar.md)*

> [atención!]\
> <b>ESTA APLICACIÓN ESTÁ EN FASE BETA, POLO QUE É POSIBLE QUE ATOPES ERROS. SE
> ISTO OCORRE, ABRE UNHA INCIDENCIA NO NOSO REPOSITORIO DE GITHUB CUBRINDO O
> MODELO DE INCIDENCIA.</b>
> 
> <b>INCLUÍR NEWPIPE, OU CALQUERA DERIVADO DEL NA GOOGLE PLAY STORE, VIOLA OS
> SEUS TERMOS E CONDICIÓNS.</b>
> 
> <b>"NewPipe" É UNHA MARCA DENOMINATIVA REXISTRADA Suxeita á [SÚA POLÍTICA DE
> MARCAS](https://newpipe-ev.de/policy/trademark/). NON SE TOLERARÁN AS
> APLICACIÓNS QUE INFRIXAN ESTA NORMATIVA.</b>

## Capturas de pantalla

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

### Servizos compatibles

NewPipe actualmente soporta estes servizos:

<!-- We link to the service websites separately to avoid people accidentally opening a website they didn't want to. -->
* YouTube ([website](https://www.youtube.com/)) e YouTube Music
  ([website](https://music.youtube.com/))
  ([wiki](https://en.wikipedia.org/wiki/YouTube))
* PeerTube ([sitio web](https://joinpeertube.org/)) e todas as súas instancias
  (visita o sitio web para saber que significa iso!)
  ([wiki](https://en.wikipedia.org/wiki/PeerTube))
* Bandcamp ([website](https://bandcamp.com/))
  ([wiki](https://en.wikipedia.org/wiki/Bandcamp))
* SoundCloud ([website](https://soundcloud.com/))
  ([wiki](https://en.wikipedia.org/wiki/SoundCloud))
* media.ccc.de ([website](https://media.ccc.de/))
  ([wiki](https://en.wikipedia.org/wiki/Chaos_Computer_Club))

Como podes ver, NewPipe é compatible con varios servizos de vídeo e son. Aínda
que comezou con YouTube, co paso dos anos outras persoas engadiron máis
servizos, facendo que NewPipe sexa cada vez máis versátil!

En parte debido ás circunstancias e en parte á súa popularidade, YouTube é o
servizo que conta cun mellor soporte entre todos eles. Se utilizas algún destes
outros servizos ou estás familiarizado con eles, axúdanos a mellorar o soporte
para os mesmos! Buscamos persoas que se encarguen do mantemento de SoundCloud e
PeerTube.

Se tes pensado engadir un servizo novo, ponte en contacto connosco primeiro! A
nosa [documentación](https://teamnewpipe.github.io/documentation/) ofrece máis
información sobre como engadir un servizo novo á aplicación e ao [NewPipe
Extractor](https://github.com/TeamNewPipe/NewPipeExtractor).

## Descrición

NewPipe funciona obtendo os datos necesarios da API oficial (por exemplo, de
PeerTube) do servizo que esteas a utilizar. Se a API oficial está restrinxida
para os nosos fins (como no caso de YouTube) ou é propietaria, a aplicación
analiza o sitio web ou utiliza, no seu lugar, unha API interna. Isto significa
que non precisas ter unha conta en ningún servizo para usar NewPipe.

Amais, ao tratarse de software libre e de código aberto, nin a aplicación nin o
Extractor utilizan bibliotecas ou marcos de traballo propietarios, como Google
Play Services. Isto significa que podes usar NewPipe en dispositivos ou ROMs
personalizadas que non teñan instaladas as aplicacións de Google.

### Características

* Ver vídeos en resolucións ata 4K
* Escoita o son en segundo plano, cargando só o fluxo de son para aforrar datos
* Modo emerxente (reprodutor flotante, tamén coñecido como «Picture-in-Picture»)
* Ver emisións en directo
* Amosar / Ocultar subtítulos / subtítulos pechados
* Busca vídeos e audios (en YouTube, tamén podes especificar o idioma do
  contido)
* Engadir vídeos á cola (e, opcionalmente, gardalos como listas de reprodución
  locais)
* Mostrar/ocultar información xeral sobre os vídeos (como a descrición e as
  etiquetas)
* Amosar / ocultar os vídeos seguintes / relacionados
* Amosar / ocultar comentarios
* Busca de vídeos, audios, canles, listas de reprodución e álbums
* Explora vídeos e audios dentro dunha canle
* Subscríbete a canles (si, sen iniciar sesión en ningunha conta!)
* Recibe notificacións sobre novos vídeos das canles ás que estás subscrito
* Crea e edita grupos de canles (para facilitar a navegación e a xestión)
* Explora fluxos de vídeo xerados a partir dos teus grupos de canles
* Consulta e busca no teu historial de visualizacións
* Busca e reproduce listas de reprodución (trátase de listas de reprodución
  remotas, o que significa que se obteñen do servizo que estás a consultar)
* Crea e edita listas de reprodución locais (estas créanse e gárdanse dentro da
  aplicación e non teñen relación ningunha con ningún servizo)
* Descarga vídeos / audios / subtítulos (subtítulos pechados)
* Abrir no Kodi
* Ver / Bloquear contido con restrición de idade

<!-- Hidden span to keep old links compatible. You should remove this span if you're translating the README into another language.-->
<span id="updates"></span>

## Instalación e actualizacións
Podes instalar NewPipe utilizando un dos seguintes métodos:
 1. Engade o noso repositorio personalizado a F-Droid e instálao dende alí.
    Podes atopar as instrucións aquí:
    https://newpipe.net/FAQ/tutorials/install-add-fdroid-repo/
 2. Descarga o APK desde [GitHub
    Releases](https://github.com/TeamNewPipe/NewPipe/releases), [compare the
    signing key](#apk-info) e instálao.
 3. Actualiza a través de F-Droid. Este é o método máis lento para obter
    actualizacións, xa que F-Droid debe recoñecer os cambios, compilar o propio
    ficheiro APK, asinalo e, finalmente, distribuír a actualización aos
    usuarios.
 4. Constrúe ti mesmo unha APK de depuración. Esta é a forma máis rápida de
    obter novas funcionalidades no teu dispositivo, pero é moito máis
    complicada; por iso, recomendamos utilizar un dos outros métodos.
 5. Se che interesa unha funcionalidade concreta ou a corrección dun erro
    incluída nun *Pull Request* (PR) neste repositorio, tamén podes descargar o
    seu APK directamente desde a propia PR. Consulta a descrición da PR para
    obter instrucións. A gran vantaxe das APK específicas dunha PR é que se
    instalan de forma independente á aplicación oficial; así, non tes que
    preocuparte por perder os teus datos nin por estragar nada.

Recomendamos o método 1 para a maioría dos usuarios. Os ficheiros APK instalados
mediante o método 1 ou o 2 son compatibles entre si (o que significa que, se
instalaches NewPipe usando o método 1 ou o 2, tamén podes actualizalo empregando
o outro método), pero non son compatibles cos instalados mediante o método 3.
Isto débese a que para os métodos 1 e 2 se utiliza a mesma clave de sinatura (a
nosa), mentres que para o método 3 se emprega unha clave diferente (a de
F-Droid). A creación dun APK de depuración (*debug*) mediante o método 4 non
inclúe ningunha clave. As claves de sinatura axudan a garantir que non se engane
o usuario para que instale unha actualización maliciosa dunha aplicación. No
caso do método 5, cada APK asínase cunha clave aleatoria distinta proporcionada
por GitHub Actions, polo que nin sequera é posible realizar actualizacións.
Terás que facer unha copia de seguridade e restaurar os datos da aplicación cada
vez que queiras utilizar un novo APK.

Mentres tanto, se por algún motivo desexas cambiar de fonte (por exemplo, se a
funcionalidade principal de NewPipe deixa de funcionar e F-Droid aínda non
dispón da última actualización), recomendamos seguir este procedemento:
1. Fai unha copia de seguridade dos teus datos a través de «Configuración >
   Copia de seguridade e restauración > Exportar base de datos» para conservar o
   teu historial, as subscricións e as listas de reprodución.
2. Desinstalar NewPipe
3. Descarga a APK da nova fonte e instálaa
4. Importa os datos do paso 1 a través de Configuración > Copia de seguridade e
   restauración > Importar base de datos

> [!Nota] Ao importar unha base de datos na aplicación oficial, asegúrate sempre
> de que sexa a mesma que exportaches _desde_ a aplicación oficial. Se importas
> unha base de datos exportada desde un APK distinto da aplicación oficial,
> poderías causar problemas no funcionamento. Esta acción non conta con
> asistencia técnica; só deberías realizala se tes a certeza absoluta de que
> sabes o que estás a facer.

### Información da APK

Esta é a pegada dixital SHA da clave de sinatura de NewPipe, que serve para
verificar os ficheiros APK descargados que foron asinados por nós. A pegada
dixital tamén está dispoñible no [NewPipe's
website](https://newpipe.net#download). Isto é relevante para o método 2.
```
CB:84:06:9B:D6:81:16:BA:FA:E5:EE:4E:E5:B0:8A:56:7A:A6:D8:98:40:4E:7C:B1:2F:9E:75:6D:F5:CF:5C:AB
```

## Contribución
Xa sexan ideas, traducións, cambios no deseño, limpeza de código ou mesmo
modificacións importantes no código, calquera axuda é benvida. A aplicación
mellora con cada contribución, sen importar se é grande ou pequena! Se queres
colaborar, consulta as nosas [notas sobre
contribucións](.github/CONTRIBUTING.md).

<a href="https://hosted.weblate.org/engage/newpipe/">
<img src="https://hosted.weblate.org/widgets/newpipe/-/287x66-grey.png" alt="Translation status" />
</a>

## Doar
Se che gusta NewPipe, podes facer unha doazón. Preferimos Liberapay, xa que é de
código aberto e sen ánimo de lucro. Para obter máis información sobre como doar
a NewPipe, visita o noso [sitio web](https://newpipe.net/donate).

<table>
  <tr>
    <td><a href="https://liberapay.com/TeamNewPipe/"><img src="https://upload.wikimedia.org/wikipedia/commons/2/27/Liberapay_logo_v2_white-on-yellow.svg" alt="Liberapay" width="80px" ></a></td>
    <td><a href="https://liberapay.com/TeamNewPipe/"><img src="assets/liberapay_qr_code.png" alt="Visit NewPipe at liberapay.com" width="100px"></a></td>
    <td><a href="https://liberapay.com/TeamNewPipe/donate"><img src="assets/liberapay_donate_button.svg" alt="Donate via Liberapay" height="35px"></a></td>
  </tr>
</table>

## Política de privacidade

O proxecto NewPipe ten como obxectivo ofrecer unha experiencia privada e anónima
ao utilizar servizos multimedia baseados na web. Por iso, a aplicación non
recompila ningún dato sen o teu consentimento. A política de privacidade de
NewPipe explica detalladamente que datos se envían e se almacenan cando envías
un informe de erro ou deixas un comentario no noso blog. Podes atopar o
documento [aquí](https://newpipe.net/legal/privacy/).

## Licenza
[![GNU GPLv3
Image](https://www.gnu.org/graphics/gplv3-127x51.png)](https://www.gnu.org/licenses/gpl-3.0.en.html)

NewPipe é software libre: podes usalo, estudalo, compartilo e melloralo como
queiras. En concreto, podes redistribuílo e/ou modificalo segundo os termos da
[Licenza Pública Xeral GNU](https://www.gnu.org/licenses/gpl.html), tal e como a
publica a Free Software Foundation, xa sexa na súa versión 3 ou (a túa elección)
en calquera versión posterior.
