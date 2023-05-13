---
layout: page
title: Shirazi, Aida (1987-)
category: incipits
century: 20th
permalink: /shirazi/
---

*Learn more about this composer at <a href="https://aidashirazi.com/" target="_blank">https://aidashirazi.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
    //Type in the last name and first name of the composer, as above//
      {% if item.author == "Shirazi, Aida" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>