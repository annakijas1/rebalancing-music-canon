---
layout: page
title: Jazwinski, Barbara (1950-)
category: incipits
century: 20th
permalink: /jazwinski/
---

*Learn more about this composer at <a href="https://barbarajazwinski.com/" target="_blank">https://barbarajazwinski.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Jazwinski, Barbara" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
