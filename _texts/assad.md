---
layout: page
title: Assad, Clarice (1978-)
category: incipits
century: 20th 
permalink: /assad/
---

*Learn more about this composer at <a href="https://clariceassad.com/" target="_blank">https://clariceassad.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Assad, Clarice" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>