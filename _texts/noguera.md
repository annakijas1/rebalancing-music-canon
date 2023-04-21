---
layout: page
title: Noguera Palaua, Carolina (1978-)
category: incipits
century: 20th
permalink: /noguera/
---

*Learn more about this composer at <a href="https://www.carolinanoguera.com/" target="_blank">https://www.carolinanoguera.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Noguera Palaua, Carolina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
