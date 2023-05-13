---
layout: page
title: Milstein, Silvina (1956-)
category: incipits
century: 20th
permalink: /milstein/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Silvina_Milstein" target="_blank">https://en.wikipedia.org/wiki/Silvina_Milstein</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Milstein, Silvina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>