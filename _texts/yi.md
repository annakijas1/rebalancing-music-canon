---
layout: page
title: Yi, Chen (1953-)
category: incipits
century: 20th
permalink: /yi/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Chen_Yi_(composer)" target="_blank">https://en.wikipedia.org/wiki/Chen_Yi_(composer)</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Yi, Chen" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
