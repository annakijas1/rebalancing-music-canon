---
layout: page
title: Washington, Shelley (1991-)
category: incipits
century: 20th
permalink: /washington/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Shelley_Washington" target="_blank">https://en.wikipedia.org/wiki/Shelley_Washington</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Washington, Shelley" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>