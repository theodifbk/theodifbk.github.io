---
title: SET, Electricity
subtitle: This dataset provides information about the current flowing through the electrical grid of the Trentino province. 
layout: default
modal-id: 18
date: 2014-12-01
img: finodex.png
thumbnail: energy.png
alt: image-alt
download: https://dandelion.eu/datagems/SpazioDati/set-electricity/resource/
type: energy
area: Trentino
category: openbigdata
SET Distribuzione SPA manages almost all the electrical network over the Trentino territory. It uses around 180 primary distribution lines (medium voltage lines) to bring energy from the national grid and distribute it among Trentino users. The dataset supplies information regarding the current flowing through the distribution lines and details about how the distribution lines are spread over the Trentino territory.
The dataset is composed by two sub-datasets:
Customer site dataset
it provides a description of the primary distribution lines serving the Trentino territory. The geometry of the lines is not explicitly exposed. The physical description of the lines is given in terms of customer sites connected to the primary distribution lines. Note that customer sites often provide energy to more than one customer. In other words, they can provide electricity to one customer (single-family houses), to many costumers (condominiums), to business activities and to public structures.
	Spatial Aggregation
	customer sites of each line are grouped by the squares of the Trentino GRID. This means that given a square of the Trentino GRID and a specific distribution line the number of customer sites falling in such a group is recorded.
	Temporal aggregation
	the topology of the network is considered to be static, therefore no temporal aggregation is provided.

Line measurement dataset
this dataset provides the amount of current flowing through the lines at specific instants

There is no spatial aggregation for this dataset.
The current flowing through the distribution lines has been recorded every 10 minutes.
---
