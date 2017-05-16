---
layout: archive
title: "Enjoy the view!"
date: 2014-05-30T11:40:45-04:00
modified:
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
