---
layout: archive
title: "Photo Gallery"
excerpt: "A collection of photos from the terrace."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.media %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
