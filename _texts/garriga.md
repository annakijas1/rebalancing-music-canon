---
layout: page
title: Garriga, Carlota (1937-)
category: incipits
century: 20th
permalink: /garriga/
---

*Learn more about this composer at <a href="https://es.wikipedia.org/wiki/Carlota_Garriga" target="_blank">https://es.wikipedia.org/wiki/Carlota_Garriga</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Garriga, Carlota" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
