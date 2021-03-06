---
layout: archive
permalink: /
title:
excerpt: "I'm a passionate web and mobile developer who &#10084; new technologies"
id: home
---

<div id="content" class="page-content" itemprop="articleBody">
  <p>
    Full-stack web and mobile developer, I help people to reach success solving their problems using agile methodologies and lean startup concepts.
  </p>

  <p>
    <a href="http://en.wikipedia.org/wiki/Ruby_%28programming_language%29" target="_blank">Ruby</a>, <a href="http://en.wikipedia.org/wiki/NodeJS" target="_blank">Node.js</a> and <a href="http://en.wikipedia.org/wiki/Laravel_%28framework%29" target="_blank">PHP</a> are my allies when working with backend.<br>

    <a href="http://en.wikipedia.org/wiki/Backbone.js" target="_blank">Backbone.js</a> and <a href="http://en.wikipedia.org/wiki/EmberJS" target="_blank">Ember.js</a> are my friends in projects that need a <em>zen workflow</em>.<br>

    <a href="http://en.wikipedia.org/wiki/Apache_Cordova" target="_blank">Apache Cordova</a> (formely PhoneGap) is my superhero for faster mobile results.
  </p>

  <p>See my opensource contributions in my <strong><a href="https://github.com/jnettome">Github</a></strong> and <strong><a href="https://coderwall.com/joaonettome">Coderwall</a></strong> profiles. Check my professional bio on <strong><a href="https://linkedin.com/in/joaonettome">Linkedin</a></strong>.</p>
</div>
<br><br>

---

### Latest Articles

<div class="tiles">
{% for post in site.categories.articles limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
