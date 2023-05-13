---
layout: page
title: Ince, Kamran (1960-)
category: incipits
century: 20th
permalink: /ince/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Kamran_Ince" target="_blank">https://en.wikipedia.org/wiki/Kamran_Ince</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ince, Kamran" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>