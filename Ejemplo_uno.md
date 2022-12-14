<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config
       title="Antigua Roma"
       author="Clase 1"
       banner="https://upload.wikimedia.org/wikipedia/commons/4/4c/Acueducto_de_M%C3%A9rida.jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q220"> <!-- Roma --> 

# Fundación mítica de Roma 

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image
       url="https://upload.wikimedia.org/wikipedia/commons/3/37/Pyrrhic_War_Map_-_English-Latin_Version.png">

# Basic usage

## Image

_La fundación de Roma se asocia a la leyenda de Luperca, Rómulo y Remo, pero también al mundo divino, griego y los troyanos. Dice la leyenda que Ascanio habría fundado la ciudad de Alba Longa en la orilla derecha del río Tíber.[^1]
<param ve-compare curtain 
       label="Romulo et Remus s "
       description="fundación mítica de Roma"
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/6/6a/She-wolf_suckles_Romulus_and_Remus.jpg">
<param ve-compare 
       label="Romulo et Remus"
       description="fundación mítica de Roma"
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/f/fb/Q._Servilius_Caepio_%28M._Junius%29_Brutus%2C_denarius%2C_54_BC%2C_RRC_433-1_reverse.jpg">

## Map

_Roma se fundó a la orilla del Río Tiber_
<param ve-entity eid="Q220">
<param ve-map center="Q220" zoom="11" show-labels marker-type="circle" radius="8" fill="#D6234A" prefer-geojson>

## Buenos Aires a Montevideo
_Viaje a Uruguay. De Buenos Aires a Montevideo. 
<param ve-entity eid="Q1486" fill="#b71a1a"> <!-- Buenos Aires, fill definido como parte de la entidad, override después-->
<param ve-entity eid="Q1335" fill="#dc882f"> <!--Montevideo, fill definido como parte de la entidad, override después-->
<param ve-map center="Q1486" zoom="6">

## Buenos Aires a Montevideo
_Viaje a Uruguay. De Buenos Aires a Montevideo. 
<param ve-entity eid="Q1486" marker-symbol="plane" label="Buenos Aires" prefer-geojson> <!-- Buenos Aires-->
<param ve-entity eid="Q1335" marker-symbol="user" label="Montevideo"> <!--Montevideo-->
<param ve-map 
center="-34.740363, -57.252039" zoom="6"
title="Viaje de Buenos Aires a Montevideo"
label="Buenos Aires - Montevideo"
basemap="Esri_WorldPhysical"
>

## Buenos Aires a Montevideo
_Viaje a Uruguay. De Buenos Aires a Montevideo. 
<param ve-entity eid="Q1486" marker-symbol="plane" label="Buenos Aires"> <!-- Buenos Aires-->
<param ve-entity eid="Q1335" marker-symbol="user" label="Montevideo"> <!--Montevideo-->
<param ve-map 
center="-34.740363, -57.252039" zoom="6"
title="Viaje de Buenos Aires a Montevideo"
label="Buenos Aires - Montevideo"
basemap="Esri_WorldGrayCanvas"
>
<param ve-map-layer geojson active title="Viaje" url="bsas-montevideo.geojson">

## Buenos Aires a Montevideo
_Viaje a Uruguay. De Buenos Aires a Montevideo. 
<param ve-map 
center="-34.740363, -57.252039" zoom="7"
title="Viaje de Buenos Aires a Montevideo"
label="Buenos Aires - Montevideo"
basemap="Esri_WorldGrayCanvas"
>
<param 
ve-map-layer geojson active title="Viaje2" 
url="bsas-montevideo4.geojson"
>

<param 
ve-map-layer geojson active title="Montevideo" 
url="Montevideo.geojson"
>

<param 
ve-map-layer geojson active title="Buenos Aires"  
url="BuenosAires.geojson"
> 
<!--Linea de tiempo con agregados -->
 
## Buenos Aires a Montevideo
_Viaje a Uruguay. De Buenos Aires a Montevideo. 
<param ve-map 
center="-34.740363, -57.252039" zoom="7"
show-labels
title="Viaje de Buenos Aires a Montevideo"
label="Buenos Aires - Montevideo"
basemap="Esri_WorldGrayCanvas"
>
<param 
ve-map-layer geojson active title="Viaje3" 
url="BuenosAires-Montevideo-1.geojson"
>

## Países en el año 1
_Límites políticos en el año 1
<param ve-map 
title="Países en el año 1BC"
basemap="Esri_WorldGrayCanvas"
>
<param 
ve-map-layer geojson active title="Año_1" 
url="cntry1bc.geojson"
>

## Rust Belt
_Mapa del Rust Belt
<param ve-map 
title="Rust Belt"
basemap="Esri_WorldGrayCanvas"
>
<param ve-map-layer mapwarper active mapwarper-id="44832" title="Kent Topo Survey 1860">

## Paises con linea de tiempo
Mapa del tamarindo con linea de tiempo
<param ve-map 
       time-dimension
       time-interval="10/"
       duration="P10000Y"
       basemap="Esri_WorldGrayCanvas"
       auto-play="false"
       zoom="2"
       max-zoom="4"
       date-format="YYYY"
       fps="1"
<param ve-map-layer geojson url="Tamarind_map.json">

## Países Criptomeria Japonica
_Expansión de la criptomeria japónica
<param ve-map 
title="Criptomeria Japónica"
basemap="Esri_WorldGrayCanvas"
>
<param 
ve-map-layer geojson active title="Azores" 
url="ne_10m_admin_1_Azores.json"
>
<param 
ve-map-layer geojson active title="CChina" 
url="ne_10m_admin_1_CentralChina.json"
>
<param 
ve-map-layer geojson active title="NZ" 
url="ne_10m_admin_1_NZNorte.json"
>
<param 
ve-map-layer geojson active title="WChina" 
url="ne_10m_admin_1_WChina.json"
>
<param 
ve-map-layer geojson active title="Japón y otros" 
url="ne_110m_admin_0_Jap_den_etc.json"
>

## Puntos en Buenos Aires

_Buenos Aires
<param ve-map 
title="Puntos Random"
center="-34.740363, -57.252039" zoom="7"       
basemap="Esri_WorldGrayCanvas"
time-dimension
       time-interval="-001000/"
       duration="P10000Y"
       auto-play="false"
       zoom="2"
       max-zoom="4"
       date-format="YYYY"
       fps="1"
show-labels>

<param 
ve-map-layer geojson active title="A" 
marker-type="circle"
radius="4" 
stroke-width="0"
fill="blue" 
fill-opacity="1"
url="map1.geojson"
>

<param 
ve-map-layer geojson active title="A"
marker-type="circle"
radius="6" 
stroke-width="0"
fill="blue" 
fill-opacity="1" 
url="map2.geojson"
>

## Nepenthes heatmap

Un heatmap que toma puntos de latitudes y longitudes
<param ve-map center="-2, 118" zoom="4">
<param ve-map-layer heatmap 
       url="nepenthes.tsv" 
       radius="2" 
       scale-radius="true" 
       use-local-extrema="true" 
       max-opacity="1">

## Mapa georreferenciado

Conflicto armado en Colombia
<param ve-map center="4.807007, -71.523247" zoom="4">
<param ve-map-layer mapwarper active mapwarper-id="68026" title="Conflicto armado en Colombia">

## Heliconia red
Red de Heliconia 


<param ve-d3plus-ring-network url="https://raw.githubusercontent.com/JSTOR-Labs/plant-humanities/main/data/heliconia_network_interactions.tsv" center="Heliconia imbricata">


## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
