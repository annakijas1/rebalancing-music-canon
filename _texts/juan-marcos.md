---
layout: page
title: Juan-Marcos, Antonio (1979-)
category: incipits
century: 20th
permalink: /juan-marcos/
---

*Learn more about this composer at <a href="https://www.antoniocomposer.com/about" target="_blank">https://www.antoniocomposer.com/about</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Juan-Marcos, Antonio" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
