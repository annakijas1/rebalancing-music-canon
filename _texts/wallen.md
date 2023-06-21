---
layout: page
title: Wallen, Errollyn (1958-)
category: incipits
century: 20th
permalink: /wallen/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Errollyn_Wallen" target="_blank">https://en.wikipedia.org/wiki/Errollyn_Wallen</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Wallen, Errollyn" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>