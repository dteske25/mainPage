---
layout: archive
permalink: /
title: "Home"
image: 
  feature: FeaturedImage1.png
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
