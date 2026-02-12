---
layout: page
title: Bertrand, Elise (2000-)
category: incipits
century: 21st
permalink: /bertrand/
---

*Learn more about this composer at <a href="https://elise-bertrand.fr/biography-english/" target="_blank">https://elise-bertrand.fr/biography-english/</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Bertrand, Elise" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
