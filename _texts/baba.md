---
layout: page
title: Baba, Noriko (1972-)
category: incipits
century: 20th
permalink: /baba/
---

*Learn more about this composer at <a href="https://www.babelscores.com/norikobaba" target="_blank">https://www.babelscores.com/norikobaba</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Baba, Noriko" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>