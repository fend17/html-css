# Instruktioner för användande av `@font-face`

1. Besök [https://fonts.google.com](https://fonts.google.com) eller [https://www.fontsquirrel.com/](https://www.fontsquirrel.com/) och ladda ner valfri gratis font. Tänk på att du måste ha rättigheter att använda fonten på nätet. Alla från dessa sidor är du tillåten att använda. På Google Fonts trycker du på nerladdningsknappen i högra hörnet när du valt en font:
![https://i.imgur.com/lsYGPeS.png](https://i.imgur.com/lsYGPeS.png)
2. Besök sedan [https://www.fontsquirrel.com/tools/webfont-generator](https://www.fontsquirrel.com/tools/webfont-generator) och ladda upp fonten som du nyss laddade ner genom att trycka på **Upload Fonts**. `.woff` samt `.woff2` borde vara ikryssat, det är de formaten vi vill ha.
![https://i.imgur.com/6Iku9C2.png](https://i.imgur.com/6Iku9C2.png)
3. Skrolla sedan ner, kryssa i checkboxen längst ner och då borde en knapp med **Download Your Kit** komma upp. Tryck på den så får du ner både fonterna som behövs i rätt format samt css-en som behövs för att ladda in dem.
![https://i.imgur.com/I1yRIxj.png](https://i.imgur.com/I1yRIxj.png)
4. Du borde ha fått ner en css-fil samt minst två stycken webfonter, din font i formaten `.woff` samt `.woff2`. Lägg fonterna i din projektmapp, där du har din hemsida. Om du lägger fonterna i en undermapp som heter t.ex. `fonts` måste du ändra sökvägen i `@font-face` så att den pekar rätt. Kopiera sedan in den cssen som ligger i css-filen `font.css` i din egna css-fil, längst upp i dokumentet.
![https://i.imgur.com/lEVajFg.png](https://i.imgur.com/lEVajFg.png)

**Tänk på att namnet på `font-family` är det som du ska använda i resten av din css. Så i detta fall så skulle jag skriva `font-family: 'rieslingregular` om jag skulle använda denna font på något ställe i min kod.**