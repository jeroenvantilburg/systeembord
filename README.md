# Online systeembord
 Deze javascript-applicatie simuleert de werking het het systeembord zoals dat wordt gebruikt in de lessen natuurkunde in de voortgezet onderwijs. Met dit programma kunnen leerlingen thuis en op school oefenen met de werking van het systeembord.


## Webapp

[![Webapp screenshot](/screenshot.png)](https://jeroenvantilburg.github.io/systeembord)

[Probeer de webapp!](https://jeroenvantilburg.github.io/systeembord)

De webapp is geschreven in HTML5 en javascript en draait in principe in Windows/MacOS/Android/iOS in iedere browser. De code is nog in ontwikkeling. Als er iets niet werkt of voor verbeteringen: geef feedback.


## Beknopte instructie

- Verbindingssnoeren maken: De snoeren moeten van een uitgang naar ingang worden getrokken. Klik op een uitgang (rode cirkel) en sleep het snoer naar een (grijze) ingang.
- Meerdere verbindingssnoeren: Een uitgang kan met meerdere ingangen worden verbonden.
- Verbindingssnoeren verwijderen: Sleep het snoer weg van de ingang.
- Drukschakelaar: Met een klik-sleep kan de schakelaar worden vastgezet.
- Relais: De relais is al aangesloten op een wisselspanningbron. De zwarte uitgangen kunnen worden verbonden met de lamp of 
de elektrische verwarming. 
- Sensoren: De geluidsensor is aangesloten op de ingebouwde microfoon van de computer (werkt niet in iOS/Safari of IE).
De LDR van de lichtsensor kan worden gesleept. De spanning is afhankelijk van de afstand tot de lamp, wanneer die aan staat. De temperatuursensor is (draadloos) verbonden met de thermometer bij de verwarming.
- Zoemer: Er zit een vertraging in de zoemer van een halve seconde. In iOS/Safari moet je eerst de zoemer handmatig initialiseren door op de play button te drukken (zie deze [discussie](https://stackoverflow.com/questions/12804028/safari-with-audio-tag-not-working)).
- Meer informatie: Zie de [handleiding](http://www.cma-science.nl/resources/nl/practicum/b0020.pdf) van het systeembord.

## Wish list

- Toevoegen van echte sensoren via USB.
- Zelf configureren van de componenten door te slepen.

## License and credits

Deze webapp simuleert het systeembord zoals dat wordt aangeboden door [CMA Science](http://cma-science.nl/).

Deze webapp gebruikt veelvuldig gebruik van de [Fabric.js](http://fabricjs.com) library.

### MIT License

```Copyright (c) 2020 Jeroen van Tilburg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
