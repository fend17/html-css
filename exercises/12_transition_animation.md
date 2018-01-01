# Transitio, Animation & Transform

Återskapa dessa animationer och övergångar genom att använda `transition`, `animation` och `transform`.

## Länkar

* [Using CSS Animations | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
* [Using CSS Transitions | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
* [Transform | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
* [http://css3.bradshawenterprises.com/](http://css3.bradshawenterprises.com/)
    * Grym playground for CSS3 Animations/Transitions/Transform

## Övningar

Övningarna är inte i någon speciell ordning gällande svårighetsgrad

### Beating heart

![Beating Heart](https://i.imgur.com/uezlQIB.gif)

_Tips_: använd `scale`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/BJZNyY)**

### V Downloader

![V Downloader](https://i.imgur.com/BlXschb.gif)

_Tips_: använd `opacity` och `translate`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/YYQXEr)**

### Bubble burst
![Bubble Burst](https://i.imgur.com/qRpkuTr.gif)

_Tips_: använd `opacity` och `scale`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/OzgVgE)**

### Subtle hover and click
![Hover on button and click](https://i.imgur.com/on4fVZM.gif)

_Tips_: använd `translate`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/yoZGzW)**

### Bobbing dots

![Bobbing loading dots](https://i.imgur.com/SSNAc6X.gif)

_Tips_: använd `animation-delay` och `translate`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/OzgVbZ)**

### Sun and cloud slide
![Sun and clouds animation](https://i.imgur.com/TrVVRj7.gif)

_Tips_: använd `animation-delay` och `translate`

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/PEjqZE)**

### Background hover transition

![Hover transition bakground](https://i.imgur.com/Na58cUX.gif)

_Tips_: använd `::before` och `::after` istället för `border`.

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/Qagboe)**

### Tooltip hover
![Tooltip hover](https://i.imgur.com/Aw6I9sd.gif)

_Tips_: använd `::before` och `::after` och [`attr()`](https://davidwalsh.name/css-content-attr)

**Lösning: [Codepen](https://codepen.io/jesperorb/pen/aEwOGm)**


### Extra: implementera loaders

Försök att implementera någon av dessa laddningsindikatorer i css:

* [**Spinkit** ~ Tobias Ahlin](http://tobiasahlin.com/spinkit/)

### Extra: Lästips

### Animista

Playground för att skapa användbara animationer i CSS. Genererar färdig CSS-kod som man kan klistra in i sin egen kod.

* [**Animista**](http://animista.net/)

#### Smooth as butter

Bra artikel om vad man ska tänka på när man animerar och kör transitions i CSS3. Vissa egenskaper är bättre än andra att animera. Ibland kan det även vara en bra idé att ta hjälp av JavaScript. `translate`, `rotate` och `scale` är skonsamma mot browsern och ger bra prestanda.

* [Smooth as Butter: Achieving 60 FPS Animations with CSS3 @ Medium](https://medium.com/outsystems-experts/how-to-achieve-60-fps-animations-with-css3-db7b98610108)
* [will-change @ MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/will-change)