# HTML-test

<details>
    <summary>1. Vad ska stå först i ett HTML-dokument? Och vad säger den kodraden om dokumentet?</summary>
    <br />
    A: <code>&lt;!DOCTYPE html&gt;</code>, det säger åt webbläsaren att rendera ut sidan på bästa möjlig sätt. Detta betyder i verklighetet i princip att den ska renderas enligt HTML5. Om man är sugen finns hela specifikation för HTML5 här: https://www.w3.org/TR/html5/
</details>

<details>
    <summary>2. Vilket/vilka element måste finnas i elementet <code>&lt;head&gt;</code>? Nämn också två valfria element som kan finnas i <code>&lt;head&gt;</code>. </summary>
    <br />
    A: <code>&lt;title&gt; &lt;meta&gt;, &lt;link&gt;, &lt;style&gt;, &lt;script&gt;</code>
</details>

3. Det finns ett antal fel `HTML`-strukturen nedan. Nämn minst **5** av dem. Några möjliga svar finns under koden.
```html
<body>
  <ul>
      <li>first item</li>
      <li><b>second item<b></li>
  </ol>
  <div>Message that should be fixed in a corner<div/>
    <div>
      <main>
         <section> <h1>The best images</h1>
        <p> Here's my favourite image: 
                 <img>http('server.com/image.gif')</img>
        </p> <!-- to do: add some more images -->
        </section>
     </main>
     <aside></aside>
</div>
<span>In conclusion: <p>To do</p> </span>
</html>
```

<details>
    <summary>3. Möjliga svar</summary>
    <br />

1. <code>&lt;ul&gt;</code>-taggen avslutas med <code>&lt;ol&gt;</code>. Kan fungera men inte korrekt.
2. <code>&lt;b&gt;</code> kan användas men i de flesta fall så kan andra mer semantiska element användas, använd i så fall `<strong>`/`<em>`/`<mark>`. [`<b>` | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b)
3. `<div/>` är inkorrekt avslutad, slash ska komma före taggen. 
4. Ett överflödigt `<div>`-element omsluter `<main>`. `<div>`- har ingen som helst funktion.
5. `<h1>` samt `<p>` inuti sectionen är felaktigt indenterad. Båda elementen ska vara indenterade ett steg innanför `<section>` då de är barn.
6. `<img>`-taggen ska ha URL:en i attributet `src`, dessutom så behöver inte `<img>` ha någon sluttagg och borde avslutas direkt `<img src="" alt=""/>`. Utöver det ska en bild alltid ha ett `alt`-attribut.
7. `<aside>` är ett tomt element, använder vi inte elementet för att märka upp innehåll, d.v.s. saknas innehållet så ska elementet inte finnas.
8. `<span>` är ett `inline`-element och `<p>` är ett `block`-element. `inline` borde förekomma inuti `block`-elementet och inte tvärtom.
</details>



<details>
    <summary>4. Nämn tre <code>inline</code>-element och när de ska användas.</summary>
    <br />

* `a` används för länkar och är inline för att kunna skrivas i löptext.
* `abbr` (abbreviation) används för förkortningar <code>&lt;abbr title=&quot;Keeping Parents Clueless&quot;&gt;KPC&lt;/abbr&gt;</code>
* `code` används för kodblock. Element med liknande användningsområden är `pre` samt `samp`.
* `em` (emphasis) används för att betona en viss text. Rent visuellt så blir det till _italics_ men ska inte användas enbart för att styla till italics.
* `span` är som textens `div`, inget värde egentligen, används ofta om du ska ha ett element i löptext som måste stylas.
* `strong` betyder att ordet eller texten innanför taggarna har en viss importans.
</details>



