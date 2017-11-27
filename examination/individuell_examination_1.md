# Individuell examination 1
> Hemsida & peer review
> 
> Betygsnivå: **G**

## Innehåll

<img src="https://i.imgur.com/ZHMA9sU.png" alt="Arboreal" height="150" width="auto" align="right">

Startup-företaget **Arboreal** behöver en ny hemsida för sin affärsidé. Ni har fått i uppdrag att skapa denna sida. 

__Arboreal__ är en prenumerationstjänst för företag. Tjänsten innebär att man får sitt kontor inrett med växter med hjälp av experter från _Arboreal_. Sedan betalar man en månadskostnad för att få nya växter levererade och placerade på kontoret varje månad eller vecka beroende på vilken prisplan man har valt. _Arboreal_ har sin kundgrupp bland små till medelstora IT-företag i stockholmsområdet.

## Mission

>Arboreal revolutionizes the way you think about plants in an office environment. Arboreal isn't just a a delivery service for plants, it's a delivery service for new ideas. Arboreal makes it easy to keep your workplace fresh and oxygenated.

## Slogan

>A workplace that is a alive create ideas that live on.

## Logotyp

Logotyper i olika färger finns i detta repository: [https://github.com/fend17/arboreal-logo](https://github.com/fend17/arboreal-logo)

#### Pricing

| Standard  | Premium | Exclusive |
|---|---|---|
| Watering not included | Watering included | Web-controlled automated watering system included |
| No change of dead plants, monthly plant change | Exchange of dead plants included, monthly plant change | Change of dead plants included, weekly plant exchange |
| | | Surveillence system for every plant. 24/7 support for emergencies |
| | | Only locally grown plants. Exotic plants flown in by private jet |

#### Themes

* __Aloha__
    + This rich theme includes exotic coconuts spilling all over the floor combined with palm trees that hang down and are always in the way of your daily workflow. This theme is very complicated, suitable for complex startups with a unclear monetizing strategy.
* __Siberia__
    + Dead plants everywhere. Plants sprayed with white color to give that cold secluded look. 
* __Exotique Nørdic__ 
    + Everything is pine and spruce. Get that Norrlands inland-look in your office. Comes with a _Christmas Decoration Extension Pack_ for the first 100 subscribers (Bears not included).

#### Contact information

* Birger Jarlsgatan 12
* Stockholm
* Tel: 08-56 57 30
* Facebook: arboreal, Twitter: @arboreal


## Krav

* Sidan använder sig av en fler-kolumns-layout.
* Du använder dig av **semantisk HTML** för att strukturera upp ditt innehåll. `<div>` ska enbart användas för styling-syfte.
* Du använder dig **inte** av _id_ för att styla din sida. Styling ska ske med `_class_` eller `<tag>`. Det ska heller inte förekomma _inline styling_ med `style`-attributet i HTML.
* Du använder dig huvudsakligen utav **flexbox** för att positionerna ditt innehåll men andra positioneringstekniker får även förekomma (såsom `float`).
* Du använder i majoritet relativa måttenheter: `%` och `rem/em`. Användandet av enheterna ska vara konsekvent, dina marginaler och padding ska inte ha massor av spridda `px`-värden (såkallade [_magic numbers_](https://csswizardry.com/2012/11/code-smells-in-css/#magic-numbers)).
* Sidan har en meny där man kan gå till de olika undersidorna. Sidan får vara en _one page_ där det inte finns några undersidor (pricing, themes, about, contact t.ex.) men då ska menyn länka till de olika rubrikerna på sidan (scrolla till rubriken).
* Sidan innehåller all information ovan om företaget, logotyp, slogan, pricing etc. Hur det är strukturerat är dock upp till dig. Tabellen behöver t.ex. inte se exakt ut som den ser ut i detta dokument utan det viktiga är att man tydligt ser innehållet och att det är väl grupperat så man ser vilken information som hör till vad. Tabellen behöver inte heller vara av typen `table`.
* Sidan innehåller ett korrekt formaterat kontaktformulär som ska vara en `<form>` där man kan fylla i **namn**, **telefonnummer**, **email**, **företag** och **meddelande**. Inputfälten ska vara av rätt `type` och ha `labels`.
* Projektet ska ha en `README.md` i rootmappen som beskriver projeket och som du även ska använda för att skriva ner återkopplingen i.
* Sidan får innehålla JavaScript men det ger inget **extra**, sidan examineras utifrån **html** och **css**.
* HTML och CSS är **korrekt indenterad**.
* HTML och CSS är **validerad** via [W3C HTML Validator](https://validator.w3.org/)/[W3C CSS Validator](https://jigsaw.w3.org/css-validator/) och ska inte innehålla varken fel eller varningar. Du ska bifoga den output du får utav valideringen i din `README.md`.

## Feedbackpunkter

Förslag på feedbackpunkter:

* Är HTMLen logiskt upplagd, korrekt indenterad och lättläst?
* Är CSSen logiskt upplagd, korrekt indenterad och lättläst?
* Tydlig namngivning av klasser så att man förstår vad det är som stylas?
* Finns det överflödig CSS? För många selektorer eller för specifika selektorer? Upprepande av egenskaper i CSSen?
* Är gränssnittet (designen) tydligt indelad och lättanvänd?
* Finns det ändringar i designen som skulle kunna underlätta användandet av sidan? Öka kontrasterna på sidan? Använd mer marginaler/padding för att göra saker luftigare? Finns det element som är ojämnt centrerade etc.?
* Övriga synpunkter

## Inlämning

* **Lämnas in senast: 8/12 23.55**

1. Du lämnar in examinationen som **`.zip`-fil** med alla tillhörande filer (`.html`, `.css`, `.jpg`/`.png`/`.svg` samt `README.md`) på Studentportalen. Dessutom ska hemsidan vara uppladdad live via [*GitHub Pages*](https://pages.github.com/) på ert GitHub-konto.
2. Efter att ni har lämnat in projektet ska ni skicka länken till koden i projektet som ligger uppe på *GitHub* till en klasskamrat. Denna klasskamrat ska sedan **ge feedback** både på _gränssnittet_ samt _koden_. Vilken klasskamrat ni ska skicka koden till finns i ett separat dokument och är bestämt av läraren.
3. Du utvärderar denna feedback och förbättrar din kod och gränssnitt på de ställen som behövs utifrån den feedback du fick. Du lägger in denna feedback i punktform (som en lista) i `README.md` i ditt projekt.
4. När du lämnar in [Individuell examination 2](individuell_examination_2.md) (se separat dokument) av denna examination ska du ha förbättrat de punkter du tidigare fick feedback på. Du ska även skriva ner i din `README.md` om vilka åtgärder du tog för att förbättra sidan utifrån den feedback du fick. **Om** du har valt att bortse från viss feedback för att du inte håller med den så ska du även då motivera det valet i din `README.md`. Men till denna inlämning behöver du inte ordna din kod efter feedbacken.

