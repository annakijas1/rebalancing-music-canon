---
layout: page
title: Vrebalov, Aleksandra (1970-)
category: incipits
century: 20th
permalink: /vrebalov/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Aleksandra_Vrebalov" target="_blank">https://en.wikipedia.org/wiki/Aleksandra_Vrebalov</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Vrebalov, Aleksandra" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>