---
layout: page
title: Al-Ahmad, Lora (1995-)
category: incipits
century: 20th
permalink: /al-ahmad/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Al-Ahmad, Lora" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>