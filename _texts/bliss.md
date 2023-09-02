---
layout: page
title: Bliss, Marilyn (1954-)
category: incipits
century: 20th
permalink: /bliss/
---

*Learn more about this composer at <a href="http://marilynbliss.com/" target="_blank">http://marilynbliss.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Bliss, Marilyn" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>