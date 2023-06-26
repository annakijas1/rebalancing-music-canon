---
layout: page
title: Balch, Katherine (1991-)
category: incipits
century: 20th
permalink: /balch/
---

*Learn more about this composer at <a href="https://www.katherinebalch.com/" target="_blank">https://www.katherinebalch.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Balch, Katherine" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
