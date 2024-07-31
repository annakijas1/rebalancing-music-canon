---
layout: page
title: Jazwinski, Barbara (1950-)
category: incipits
century: 20th
permalink: /jazwinski/
---

//insert the wikipedia link below in the two spots as identified//
*Learn more about this composer at <a href="https://barbarajazwinski.com/" target="_blank">https://barbarajazwinski.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
    //Type in the last name and first name of the composer, as above//
      {% if item.author == "Jazwinski, Barbara" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
