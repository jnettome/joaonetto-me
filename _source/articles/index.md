---
layout: archive
title: "Articles"
date: 2014-06-02T12:26:34-04:00
modified:
excerpt: "My personal sight about tech and challenges."
image:
  feature:
  teaser:
  thumb:
id: articles  
---

<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

