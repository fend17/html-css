# Gruppexamination
> IT-byrå
> 
> Betygsnivå: **IG/G/VG**

## Introduktion

Denna examination bygger vidare på examinationen i _Bildbehandling för Webbutvecklare_. Ni ska i samma grupp som tidigare nu implementera den hemsidan ni gjorde mockups samt göra detta på ett agilt arbetssätt. Ni ska använda er utav **git** samt **sass** när ni skapar sidan.

## Arbetsmetod

Ni ska använda en agil arbetsmetod när ni arbetar med uppgiften. Hur ni arbetar med uppgiften ska i förväg vara bestämt och uppskrivet i projektets **README**. Vilket sätt ni ska arbeta är upp till er men ni ska ha en _backlog_ uppsatt i _Trello_ eller liknande verktyg som ni sedan antingen delar upp i sprintar eller jobbar utifrån en Kanban-liknande metod. Att ni sedan följer er arbetsmetod är en del av uppgiften, ni får inte frångå arbetsmetoden. Detta verifieras genom att ni en gång i veckan ska ha en avstämning med läraren då samtliga medlemmar ska vara på plats och berätta hur arbetet fortlöper.

## Versionhantering

Projektet ska versionshanteras via **GIT** och delas mellan medlemmarna i gruppen via _GitHub_ eller liknande tjänst. Det är viktigt att ni redan från start flitigt använder utav _git_ då jag kommer att kolla på historiken för att se hur mycket varje person i gruppen har bidrat.

## SASS

Projektet ska använda sig utav **SASS** som preprocessor. Ni använder er utav _nesting_, _variabler_, _mixins_ samt _partials_ samt annan funktionalitet som kommer med sass. Ni får antingen använda det direkt via terminalen eller via verktyg som [Scout App](http://scout-app.io/).

## `.gitignore`

Alla repositories ska ha en `.gitignore`-fil som säger till `git` vilka filer som ska ignoreras. Detta är det första som ska göras i ert repository om ni vill undvika problem vid merge. **Viktigt att lägga till era `.css`-filer i `.gitignore` när ni använder sass, detta ska ni göra direkt. Filer som är autogenererade ska inte vara en del av ert repository**

_Exempel:_
```
.sass-cache/
css/
*.css.map
*.css
.DS_Store
```

## Krav

* Sidan är responsiv och är uppbyggd utifrån tankesättet: **Mobile First**. Detta går att bekräfta via sättet ni har skrivit era media queries och hur ni har strukturerat ert innehåll.
* Projektet ska använda sig utav **SASS** som preprocessor. Ni använder er utav _nesting_, _variabler_, _mixins_ samt _partials_ samt annan funktionalitet som kommer med sass.
* Sidan anpassar sig utifrån **mobil**, **tablet** samt **desktop**.
* Ni använder er utav **semantisk HTML** för att strukturera upp ert innehåll. `<div>` ska enbart användas för styling-syfte.
* Ni använder er **inte** av _id_ för att styla din sida. Styling ska ske med `_class_` eller `<tag>`. Det ska heller inte förekomma _inline styling_ med `style`-attributet i HTML.
* Ni använder er huvudsakligen utav **flexbox** för att positionerna ert innehåll men andra positioneringstekniker får även förekomma (såsom `float` och `grid`). Positioneringstekniker så som `float` måste förekomma för att anpassa sidan för äldre browsers.
* Ni använder i majoritet relativa måttenheter: `%/vh/vw` och `rem/em`. Användandet av enheterna ska vara konsekvent, era marginaler och padding ska inte ha massor av spridda `px`-värden (såkallade [_magic numbers_](https://csswizardry.com/2012/11/code-smells-in-css/#magic-numbers)).
* Sidan har en meny där man kan gå till de olika undersidorna. Sidan får vara en _one page_ där det inte finns några undersidor men ska ändå då ha en meny för navigering på sidan.
* Sidan är tillgänglighetsanpassad (bilder har alt-attribut, formulär har labels, färger har tillräcklig kontrast etc.) och går igenom [WAVE](http://wave.webaim.org/) utan error eller varningar. Detta kan även kollas via andra externa verktyg så som [tota11y](http://khan.github.io/tota11y/). 
* Sidan får innehålla JavaScript men det ger inget **extra**, sidan examineras utifrån **html** och **css**.
* HTML och CSS är **korrekt indenterad** och har en logisk struktur.
* Ni har testat sidan i flera olika browsers och sidan har ett konsekvent beteende och design: **Safari**, **Chrome**, **Firefox**, **Opera**, **Microsoft Edge** samt **Internet Explorer 11/10/9/8** (viss variation får förekomma men inga större fel ska synas).
* Sidan fungerar väl på på både **Android** (Android Browser, Chrome for Android) samt **iOS** (Safari iOS, iOS Chrome).
* Sidan ska vara upplagd live via **GitHub Pages**

## Inlämning & presentation

**Lämnas in:** 30/1 23.59
**Lämnas in via studentportalen som `.zip`**

Ni lämnar in hela projektmappen som en `.zip`-fil samt länkar till det repository som ni har använt er utav under utvecklingsperioden som en kommentar vid inlämningen. Namnet på mappen som ni lämnar in (den som ni zippar) ska ha er grupps namn. I er README ska det även stå med alla medlemmars namn. Projektets mappnamn ska alltså inte vara "projekt", "grupparbete", "html css grupparbete" eller dylikt. Det får inte heller förekomma några mellanslag i varken filnamn eller mappnamn, ni ska använda någon typ av casing vid namngivningen.

Ni får även gärna lägga upp er färdiga hemsida under organisationen **FEND17** på GitHub efter att kursen är slut. Detta är dock inget krav.

#### Presentation

Ni ska vid sista lektionstillfället dema er sida samt berätta kortfattat om arbetets gång. Mer information läggs upp närmare presentationstillfället.

