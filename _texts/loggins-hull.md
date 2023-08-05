---
layout: page
title: Loggins-Hull, Allison 
category: incipits
century: 20th
permalink: /loggins-hull/
---

*Learn more about this composer at <a href="https://allisonloggins.com/" target="_blank">https://allisonloggins.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Loggins-Hull, Allison" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>