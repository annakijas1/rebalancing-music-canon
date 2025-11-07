---
layout: page
title: Stankovych, Yevhen Fedorovych (1942-) | Станко́вич, Євге́н Фе́дорович 
category: incipits
century: 20th
permalink: /stankovych/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Yevhen_Stankovych" target="_blank">https://en.wikipedia.org/wiki/Yevhen_Stankovych</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Stankovych, Yevhen" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>