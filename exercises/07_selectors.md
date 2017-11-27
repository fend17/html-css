# Selectors

## CSS Diner

Spela igenom CSS Diner för att få lite bättre koll på CSS-selektorer

* [**CSS Diner - Where we feast on selectors**](https://flukeout.github.io/)

## Återskapa layout utan class eller ID

Du ska återskapa denna layout utan att använda varken `class` eller `id`. Du får inte göra ändringar i HTML utan bara använda dig utav css. HTMLen är nedanför bilden. Klicka på bilden för att få i större upplösning.

![Blade Runner](https://i.imgur.com/iKAmLkW.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="selector-test.css">
  <title>Selector Test</title>
</head>
<body>
    <section>
        <h1>Blade Runner</h1>
        <p>I have seen things you people wouldn't believe.</p>
        <p><span>Attack ships onfire</span> off the <span>shoulder</span> of <span>Orion</span>.</p> 
        <p>I watched <em>C-beams</em> glitter in the dark near the <em>Tannhäuser Gate</em>.</p>
        <p><strong> All those moments will be lost in time, <span>like tears in rain</span>. Time to die.</strong></p>
        <img src="https://i.imgur.com/9W1c9bX.png" alt="A picture of Roy in the rain.">
        <img src="https://i.pinimg.com/originals/e7/d3/45/e7d345498391ca226a451a4c5b15e3ff.jpg" alt="A picture of Roy in the rain"></img>
        <h2>Todo List</h2>
        <ul>
          <li> Eliminate
            <ol>
              <li>Deckard</li>
              <li>That sheep</li>
            </ol>
          </li>
          <li>Freedom</li>
          <li>Take a beating in the rain </li>
          <li> Sheep names
            <ol>
              <li> Esmeralda </li>
              <li> Bääää </li>
            </ol>
          </li>
        </ul>
      </section>
      <footer>
        <p>Read more</p>
        <a href="http://www.imdb.com/title/tt0083658/">IMDB</a>
        <a href="">Bladrunner Wikia</a>
        <a href="https://en.wikipedia.org/wiki/Blade_Runner">Wikipedia</a>
        <a href="">Rotten tomatoes</a>
      </footer>
</body>
</html>
```