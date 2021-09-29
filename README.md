#  Tile Grid Map of the 299 Constituencies of Germany 

Manuell erstellte Kachelkarte (*Tile Grid Map* oder *Geo Grid*) der Wahlkreise Deutschlands zur freien Nutzung.  
Designt von Cédric Scherer und Ansgar Wolsing. Im Fall der Nutzung würden wir uns über einen Credit freuen.

*Manually created tile grid map (or geo grid) of Germany's electoral districts for free use.*  
*Designed by Cédric Scherer and Ansgar Wolsing. In case of use we would appreciate a credit.*

![](https://raw.githubusercontent.com/bydata/btw_tilemap/main/plots/grid_laender_variants_de.png)
![](https://raw.githubusercontent.com/bydata/btw_tilemap/main/plots/grid_laender_variants_en.png)

#

### Warum eine Tile Grid Map?

Die Wahlkreise sind so konzipiert, dass sie in etwa die gleiche Anzahl an Menschen umfassen. Auf einer traditionellen Karte jedoch wird die Fläche visualisiert, nicht die Anzahl der Wählenden oder der Gewählten. Somit verzerren die traditionellen Choropleth-Karten die Wahrnehmung, indem ländliche Regionen mit geringer Bevölkerungsdichte viel größere Farbflächen bieten als urbane Gebiete.  
In unserer Tile Grid Map ist jeder Wahlkreis gleich groß und die Wahrnehmung ist somit uniform. Dadurch lassen sich eben auch Ergebnisse und Trends in den urbanen Regionen ohne Probleme darstellen.

Ebenfalls ist eine [Hexbin Map via PitchInteractive](https://pitchinteractiveinc.github.io/tilegrams/) verfügbar, allerdings sind wir mit der Form Deutschlands und der Lage einiger Wahlkreise nicht zufrieden. In unserer Tile Grid Karte haben wir größte Sorgfalt darauf gelegt, die räumlichen Verhältnisse so gut es geht einzuhalten. 

### *Why a tile grid map?*

*Constituencies are designed to contain roughly the same number of people. On a traditional map, however, the area is visualized, not the number of people voting or elected. Thus, traditional choropleth maps distort perception by providing rural areas with low population density much larger areas of color than urban areas.  
In our Tile Grid Map, each constituency is the same size and the perception is thus uniform. This makes it possible to show results and trends in urban regions without any problems.*

*There is also a [hexbin map via PitchInteractive](https://pitchinteractiveinc.github.io/tilegrams/) available, but we were not happy with the shape of Germany and the location of some constituencies. In our tile grid map, we have taken great care to keep the spatial relationships as close as possible.*

#

### Glossary

| Variable  | Beschreibung | Description |
| --- | --- | --- |
| `wk_full`  | Kompletter Name des Wahlkreises  | Full name of the constituency |
| `wk`  | Name des Wahlkreises ohne Nummer  | Name of the constituency without ID |
| `id` | Wahlkreis-Nummer | Constituency ID |
| `bundesland_de` | Deutscher Name des Bundeslandes | German name of the federal state |
| `bundesland_en` | Englischer Name des Bundeslandes | English name of the federal state |
| `col` | x-Koordinate | x position |
| `row` | y-Koordinate | y position |

#

### Tools

Erstellt mit Hilfe des [Geo Grid Designer](https://hafen.github.io/grid-designer/) von Ryan Hafen und R.   
*Created using the [Geo Grid Designer](https://hafen.github.io/grid-designer/) by Ryan Hafen and R.*

***

#### Creative Commons Attribution 4.0 International License (CC BY 4.0)
<div style="width:300px; height:200px">
<img src=https://i.creativecommons.org/l/by/4.0/88x31.png alt="" height="42">
</div>
