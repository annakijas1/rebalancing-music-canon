---
layout: page
title: Ortiz, Gabriela (1964-)
category: incipits
century: 20th
permalink: /ortiz/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Gabriela_Ortiz" target="_blank">https://en.wikipedia.org/wiki/Gabriela_Ortiz</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ortiz, Gabriela" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
