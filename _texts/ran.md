---
layout: page
title: Ran, Shulamit (1949-)
category: incipits
century: 20th
permalink: /ran/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Shulamit_Ran" target="_blank">https://en.wikipedia.org/wiki/Shulamit_Ran</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ran, Shulamit" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>