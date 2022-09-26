<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config
       title="Antigua Roma"
       author="Clase 1"
       banner="https://commons.wikimedia.org/wiki/File:Acueducto_-_panoramio_(1)_edited.jpg#/media/File:Acueducto_-_panoramio_(1)_edited.jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Fundación mítica de Roma 

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_La fundación de Roma se asocia a la leyenda de Luperca, Rómulo y Remo, pero también al mundo divino, griego y los troyanos. Dice la leyenda que Ascanio habría fundado la ciudad de Alba Longa en la orilla derecha del río Tíber.[^1]
<param ve-image
       label="Romulo et Remus"
       description="fundación mítica de Roma"
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/6/6a/She-wolf_suckles_Romulus_and_Remus.jpg">

## Map

_Roma se fundó a la orilla del Río Tiber_
<param ve-map center="Q220" zoom="10">

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
