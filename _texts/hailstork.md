---
layout: page
title: Hailstork, Adolphus (1941)
category: incipits
century: 20th 
permalink: /hailstork/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Adolphus_Hailstork" target="_blank">https://en.wikipedia.org/wiki/Adolphus_Hailstork</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Hailstork, Adolphus" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>