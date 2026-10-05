# Labo 2 - reflecties

Naam: (Eric Varela)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: <a href="#adopteren">Adopteren</a> <a href="#rassen">Onze bewoners</a
<a> href="#uren">Openingsuren</a

- b. `article > p`: <p class="intro">Een dier adopteren doe je niet op een namiddag. Kom eerst langs, wandel eens met een hond of zit een halfuur bij de katten.</p>
        <p>Daarna maken we samen een afspraak voor een tweede bezoek. Pas dan beslissen we, samen met jou, of het klikt. Meer over de procedure lees je op <a href="https://www.zonnehoek.be/adoptie">onze adoptiepagina</a>.</p> <p>Op dit moment wonen er een veertigtal dieren in het asiel. De meeste zijn kruisingen; de lijst hieronder geeft de grote groepen.</p> 
        <p>Je kan zonder afspraak langskomen op deze momenten. Bel op voorhand als je een specifiek dier wil zien: <a href="tel:+3232000000">03 200 00 00</a>.</p>

- c. `.uren li:nth-child(3)`:  <li>woensdag: 14-18u</li> 
- d. `h2 ~ p`: <p>Op dit moment wonen er een veertigtal dieren in het asiel. De meeste zijn kruisingen; de lijst hieronder geeft de grote groepen.</p> <p>Je kan zonder afspraak langskomen op deze momenten. Bel op voorhand als je een specifiek dier wil zien: <a href="tel:+3232000000">03 200 00 00</a>.</p>
        
        
- e. `.rassen li:first-child`: <li>Honden

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |herkomst | | |
| 2 |blauw |volgorde | | |
| 3 |rood |specificiteit | | |
| 4 |rood| volgorde| | |
| 5 |blauw |specificiteit | | |
| 6 |blue |specificiteit | | |
| 7 |rood |herkomst | | |
| 8 |blauw|html code | | |
| 9 |rood |important | | |
| 10 |Groen |Syntax fout | | |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?) 8 een 9... ik had die html code niet gezien een wist niet dat important! voor elke regel kwam.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class? Nav a, omdat ik de links specifiek moest bewerken.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
h1,h2,h3 die waren vetter dan het referentie, ik wist niet font-weight: normal; moest gebruiken ik dach dat de tekst staandard normaal maar voor koppen blijkbaar niet.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
