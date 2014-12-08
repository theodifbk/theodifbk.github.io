---
title: Precipitation - Milano
subtitle: The dataset describes precipitation intensity and type over the city of Milan
owner: ARPA
layout: default
modal-id: 6
date: 2014-12-01
img: finodex.png
thumbnail: weather.png
alt: image-alt
download: https://dandelion.eu/datagems/SpazioDati/precipitation-milano/resource/
type: weather
license: CC BY 2.5 IT
area: the city of Milan
The dataset describes precipitation intensity and type over the city of Milan.
This dataset provides information about precipitation intensity and type over the city of Milan. This information is derived from the images provided by ARPA (Agenzia Regionale per la Protezione dell’Ambiente) at the following websites:
- [Precipitation intensity](http://www.arpa.piemonte.it/rischinaturali/tematismi/meteo/osservazioni/radar/intensita-precipitazione.html?delta=0) 
- [Precipitation type](http://www.arpa.piemonte.it/rischinaturali/tematismi/meteo/osservazioni/radar/tipo-precipitazione.html?delta=0)
The precipitation intensity ranges among the following values:
- 0 Absent (0mm)
- 1 Slight (between 0mm and 2mm)
- 2 Moderate (between 2mm and 10mm)
- 3 Heavy (between 10mm and 100mm)
The precipitation type can assume a value among:
- 0 Absent
- 1 Rain
- 2 Snow
Spatial Aggregation
The area of Milan corresponding to the borders of the Milano GRID has been partitioned in four quadrants which we refer with ids 1,2,3 and 4 as shown in Figure 1. In order to provide an overlay between this partitioning and those obtained with the Milano GRID we give a description of each quadrant in terms of the square of the Milano GRID that it covers:

The quadrant with id 1 covers the squares with the following ids:
y * 100 + x with x in [1,50] and y in [50,99]

The quadrant with id 2 covers the squares with the following ids:
y * 100 + x with x in [51,100] and y in [50,99]

The quadrant with id 3 covers the squares with the following ids:
y * 100 + x with x in [51,100] and y in [0,49]

The quadrant with id 4 covers the squares with the following ids:
y * 100 + x with x in [1,50] and y in [0,49]

Figure 1 – Quadrants used to partition the city of Milan
![MeteoMilano](MeteoMilano.png)
 
Temporal Aggregation
Precipitation intensity and type values are provided every ten minutes.
---
