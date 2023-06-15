---
layout: page
title: Scott, Jeff (1967-)
category: incipits
century: 20th
permalink: /scott/
---

*Learn more about this composer at <a href="musicbyjeffreyscott.com" target="_blank">musicbyjeffreyscott.com</a>*


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Scott, Jeff" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
