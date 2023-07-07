---
layout: page
title: Alberga, Eleanor (1949-)
category: incipits
century: 20th
permalink: /alberga/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Eleanor_Alberga" target="_blank">https://en.wikipedia.org/wiki/Eleanor_Alberga</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Alberga, Eleanor" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>