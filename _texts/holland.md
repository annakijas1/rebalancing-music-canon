---
layout: page
title: Holland, Jonathan Bailey (1974-)
category: incipits
century: 20th
permalink: /holland/
---

*Learn more about this composer at <a href="https://www.jonathanbaileyholland.com/" target="_blank">https://www.jonathanbaileyholland.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Holland, Jonathan Bailey" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
