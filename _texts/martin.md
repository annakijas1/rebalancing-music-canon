---
layout: page
title: Martin, Theresa (1979-)
category: incipits
century: 20th
permalink: /martin/
---

*Learn more about this composer at <a href="https://www.theresamartin.net/" target="_blank">https://www.theresamartin.net/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Martin, Theresa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
