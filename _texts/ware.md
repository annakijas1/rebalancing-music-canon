---
layout: page
title: Ware, Lawren Brianna (1994-)
category: incipits
century: 20th
permalink: /ware/
---

*Learn more about this composer at <a href="https://www.lbwaremusic.com/" target="_blank">https://www.lbwaremusic.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ware, Lawren Brianna" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>