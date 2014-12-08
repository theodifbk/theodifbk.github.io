---
title:  MilanoToday
subtitle: This dataset contains all the articles published on the website milanotoday.it from 01/11/2013 to 31/12/2013. 
owner: Citynews
layout: default
modal-id: 8
date: 2014-12-01
img: finodex.png
thumbnail: news.png
alt: image-alt
download: https://dandelion.eu/datagems/SpazioDati/milanotoday/description/
type: news
license: ODbL 1.0
area: Milano
category: openbigdata
This dataset contains all the articles published on the website milanotoday.it from 01/11/2013 to 31/12/2013.
The values are not spatially aggregated.
The temporal aggregation values are discrete.
MilanoToday schema
Name|Type|Description
title|String|Title of the article Concerto Capodanno in piazza Duomo: 'Lasciate a casa i botti'
link|String|Link to the original article http://www.milanotoday.it/eventi/concerti/eventi-capodanno-2014-milano.html
model|String|Model of the original article. Possible values are: article, event, press release, blog, advisory, video. press release
topic|String|Topic of the article expo 2015
date|String|Publication date, formatted according to ISO 8601 2013-12-11T11:04:50+01:00
timestamp|Integer|Unix timestamp generated from the publication date 1389778764
municipality|composite
municipality.acheneID|String| Dandelion achene for the municipality. This can be used to query the Administrative Regions dataset. http://dandelion.eu/resource/5e41093fca959d6a74eacce082179f8faa49f451
municipality.name|Strin|Name of the municipality Milano
address|String|Street address of the event described in the article Via Roma
location|String|Location of the event described in the article. When available it is something like a public location or a famous monument Porta Romana
geometry|Geometry| Coordinates of the event described in the article. Not always available. Expressed as a geojson point and projected in WGS84 (EPSG:4326) ('type': 'Point', 'coordinates': [9.116044, 45.543999]}
---
