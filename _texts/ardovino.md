---
layout: page
title: Ardovino, Lori (1960-)
category: incipits
century: 20th
permalink: /ardovino/
---

*Learn more about this composer at <a href="https://loriardovino.com/" target="_blank">https://loriardovino.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ardovino, Lori" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>