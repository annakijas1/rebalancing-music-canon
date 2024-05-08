---
layout: page
title: Perry, Zenobia Powell (1908-2004)
category: incipits
century: 20th
permalink: /perry-z/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Zenobia_Powell_Perry" target="_blank">https://en.wikipedia.org/wiki/Zenobia_Powell_Perry</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Perry, Zenobia Powell" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
