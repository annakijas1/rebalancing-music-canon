---
layout: page
title: Briz, Anna (1981-)
category: incipits
century: 20th
permalink: /briz/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Briz, Anna" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>