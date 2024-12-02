---
layout: page
title: Colasanti, Silvia (1975-)
category: incipits
century: 20th
permalink: /colasanti/
---
*Learn more about this composer at <a href="https://www.silviacolasanti.com/biography-2/?lang=en" target="_blank">https://www.silviacolasanti.com/biography-2/?lang=en</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Colasanti, Silvia" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>