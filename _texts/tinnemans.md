---
layout: page
title: Tinnemans, Jobina (1975-)
category: incipits
century: 20th
permalink: /tinnemans/
---

*Learn more about this composer at <a href="https://jobinatinnemans.com/about-2/" target="_blank">https://jobinatinnemans.com/about-2/</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Tinnemans, Jobina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
