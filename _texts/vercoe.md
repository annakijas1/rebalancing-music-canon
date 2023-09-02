---
layout: page
title: Vercoe, Elizabeth (1941-)
category: incipits
century: 20th
permalink: /vercoe/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Elizabeth_Walton_Vercoe" target="_blank">https://en.wikipedia.org/wiki/Elizabeth_Walton_Vercoe</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Vercoe, Elizabeth" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>