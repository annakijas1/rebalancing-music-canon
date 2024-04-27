---
layout: page
title: Hlinová, Karolína (2001-)
category: incipits
century: 21st
permalink: /hlinova/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Hlinová, Karolína" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>