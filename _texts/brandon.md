---
layout: page
title: Brandon, Jenni (1977-)
category: incipits
century: 20th
permalink: /brandon/
---

*Learn more about this composer at <a href="https://jennibrandon.com/" target="_blank">https://jennibrandon.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Brandon, Jenni" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>