---
layout: default 
permalink: /
title: "FBK - Open Data Institute node"
---
![odi network](../images/odi_network.png)

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
