---
layout: page
title: Fairlie-Kennedy, Margaret (1925-2013)
category: incipits
century: 20th
permalink: /fairlie-kennedy/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Fairlie-Kennedy, Margaret" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>