---
layout: archive
title: "Work"
date: 2014-06-02T15:05:16-04:00
modified:
excerpt: "Look the websites, products, apps and a lot more done by me."
image:
  feature:
  teaser:
  thumb:
id: work
---

<div class="tiles">
{% for post in site.categories.work %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

