---
layout: page
title: Browse by Ensemble Type
permalink: /solo/
---
<div class="toc">

<h3>Solo Instrument</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.ensemble == "solo" %}
          <li class="text-author.text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.author }} -
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
</div>
