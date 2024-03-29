# Waar kan ik het meeste vinden over..
<a href="https://gyazo.com/cfee7d041d6f9188b1c221c8ed895d63"><img src="https://i.gyazo.com/cfee7d041d6f9188b1c221c8ed895d63.gif" alt="Image from Gyazo" width="1000"/></a>
## Live demo
[Bekijk de demo](https://eyobdejene.github.io/frontend-data/)

## Concept
Met deze visualisatie kan de bezoeker van het museum er achter komen hoeveel objecten van bepaald onderwerp zijn te 
vinden in het museum.<br>
De objecten worden op basis van hun continent gecategoriseerd<br>
De bezoeker kan met behulp van zijn of haar eigen input het onderwerp invoeren om er achter te komen waar de meeste 
objecten vandaan komen.<br>
[Lees meer](https://github.com/EyobDejene/frontend-data/wiki/Concept)

## Doelgroep
Deze visualisatie is gemaakt voor de bezoekers van het museum.
Als bezoeker heb je misschien een voorkeur voor bepaalde objecten die je graag wil zien.
Aangezien het museum verdeelt is in continenten heb ik de objecten in de visualisatie gecategoriseerd
op basis van hun continent.
De visualisatie is handig om te gebruiken bij het vinden van de objecten binnen het museum.
Niet alle objecten zijn te vinden in het museum daarom zou het ook prettig zijn om te kunnen zien of de objecten 
tentoon worden gesteld.

## Data gebruik &  verwerking
Data is afkomstig van het NMVW. De NMVW heeft de data beschikbaar gemaakt voor ons om er mee te werken.
In de collectie verschillende objecten te vinden over verschillende continenten.
Ik heb er voor gekozen om alle objecten op te halen per continent op basis van de termmaster.
Het opschonen en categoriseren heb doormiddel van vanilla javascript gedaan.
Van alle objecten die worden opgehaald heb ik er voor gezorgd dat de 10 objecten met de meeste resultaten 
gecategoriseerd worden op basis van het continent.


**Sparql**<br>
Via SparQL queries (RDF gebaseerde gegevens) is het mogelijk om bepaalde informatie uit de verzameling van 
wereldculturen op te vragen.<br>
[Lees meer](https://github.com/EyobDejene/frontend-data/wiki/Data-query)

## Features
* Fetch data van collectie database
* Zoom-in op bubble
* Filter op meerdere continenten
* Barchart visualisatie
* Zoeken 

## Toekomstie features
* Live zoek suggesties
* Zoeken op categorie thema's

## Code snippets

* [Code snippets](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets)
* [Fetch data d3](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#fetch-data)
* [Data omzetten](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#data-omzetten)
* [Bubbles svg](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#bubbles-svg-d3)
* [Filter](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#filters)
* [Zoom](https://github.com/EyobDejene/frontend-data/wiki/Zoom)
* [Barchart](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#barchart)
* [Bar indicator](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#functie-update-pijl-boven-barchart)
* [Tooltip](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#tooltip)
* [Enter,Update, Exit pattern](https://github.com/EyobDejene/frontend-data/wiki/Code-snippets#functie-drawbars---enter)

## Documentatie

* [Functional pattern](https://github.com/EyobDejene/frontend-data/wiki/Opschonen-enqu%C3%AAte-data) 
* [Werken met svg](https://github.com/EyobDejene/frontend-data/wiki/D3--experimentals#svg-smiley)
* [Wat is D3.js](https://github.com/EyobDejene/frontend-data/wiki/D3--experimentals#wat-is-d3)
* [Wat zijn D3 patterns](https://github.com/EyobDejene/frontend-data/wiki/Enter,-Update,-Exit-pattern#enter-update-exit-pattern)

## Wiki
Lees [wiki](https://github.com/EyobDejene/frontend-data/wiki) voor het hele proces. 

# Verder ontwikkelen
Wil je verder werken aan het project of een eigen versie van het bestaande project willen maken dan is het 
noodzakelijk om de volgende sofware vooraf geïnstalleerd te hebben:

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (met npm)
* [Google Chrome](https://google.com/chrome/)

## Installatie
* `git clone <repository-url>`
* `cd frontend-data`
* `npm install`

### Build
Het project maakt gebruik van een module bundler genaamd [rollup](https://rollupjs.org/) .
Het compiles kleine stukjes code in een één complex bestand.
Het gebundelde bestand komt terrecht in het build mapje.

* `npm run build`

### Development omgeving
Automatisch bundelen van javascript bestanden bij iedere verandering

* `npm run dev`

### Deploying
Om het project te deployen kan je gebruik maken van githubpages.
GitHub Pages is een statische site-hostingservice die HTML-, CSS- en JavaScript-bestanden rechtstreeks uit een 
repository op GitHub haalt en de bestanden desgewenst via een buildproces uitvoert en een website publiceert
* [Deploy de app op githubpages](https://pages.github.com/)

## Gebruikte bronnen / Handige links
* [Documentation D3.js](https://github.com/d3/d3/wiki)
* [Introduction to D3.js](https://www.xenonstack.com/blog/d3js/)
* [d3indepth](https://www.d3indepth.com/force-layout/)
* [Naustud.io](https://naustud.io/tech-stack/)
* [Responding to text](https://bl.ocks.org/curran/a683a360b9c78397a0db94ce15f473ce)
* [Introduction SVG](https://learn-the-web.algonquindesign.ca/courses/web-dev-3/svg-smiley-face/)
* [Bar Chart animated](https://bl.ocks.org/bytesbysophie/952a1003dd188410e9c6262b68a65f9a)
* [barplot in d3.js](https://www.d3-graph-gallery.com/graph/barplot_basic.html)
* [Filtering data d3](https://bl.ocks.org/fabiomainardi/00fd581dc5ba92d99eec)
* [Zoom function](https://observablehq.com/@d3/programmatic-zoom)
* [Tooltip](http://bl.ocks.org/biovisualize/1016860)
* [Force](https://www.d3indepth.com/force-layout/)


## Credits
*  Datavisual voorbeeld van [trongthanh](https://github.com/trongthanh/techstack)
*  Example barchart pattern  [Razpudding](https://beta.vizhub.com/Razpudding/4a61de4a4034423a98ae79d0135781f7?edit=files&file=index.js)

