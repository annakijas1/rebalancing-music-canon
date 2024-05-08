---
layout: page
title: Perry, Julia (1924-1979)
category: incipits
century: 20th
permalink: /perry-j/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Julia_Perry" target="_blank">https://en.wikipedia.org/wiki/Julia_Perry</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Perry, Julia" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
