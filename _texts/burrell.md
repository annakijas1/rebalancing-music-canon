---
layout: page
title: Burrell, Diana (1948-)
category: incipits
century: 20th
permalink: /burrell/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Diana_Burrell" target="_blank">https://en.wikipedia.org/wiki/Diana_Burrell</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Burrell, Diana" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>