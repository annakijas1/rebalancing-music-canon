---
layout: page
title: Koh, Emily (1986-)
category: incipits
century: 20th
permalink: /koh/
---

*Learn more about this composer at <a href="https://emilykoh.net/" target="_blank">https://emilykoh.net/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Koh, Emily" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>