---
layout: archive
permalink: /
title:
excerpt: "I'm a passionate web and mobile developer who &#10084; new technologies"
id: home
---

<div id="content" class="page-content" itemprop="articleBody">
  <p>
    Full-stack web and mobile developer (living in Brazil), I help people to reach success solving their problems using agile metodologies and lean startup concepts.
  </p>

  <p>
    I like to work using <a href="#">Ruby</a>, <a href="#">Node.js</a> or <a href="#">PHP</a> for backend.<br>

    <a href="#">Backbone.js</a> and <a href="#">Ember.js</a> are my friends in succeed projects that needed a <em>zen workflow</em>.<br>

    <a href="#">Apache Cordova</a> (formely PhoneGap) is my superhero for faster mobile results.
  </p>

  <p>You can see my opensource contributions in my <strong><a href="https://github.com/jnettome">Github</a></strong> and <strong><a href="#">Coderwall</a></strong> profiles, my professional bio on <strong><a href="#">Linkedin</a></strong>.</p>
</div>
<br><br>

### Selected Works

<div class="tiles">
{% for post in site.categories.works limit:3 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

---

### Latest Articles

<div class="tiles">
{% for post in site.categories.articles limit:3 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
