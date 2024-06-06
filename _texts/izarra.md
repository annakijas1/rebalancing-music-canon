---
layout: page
title: Izarra, Adina (1959-)
category: incipits
century: 20th
permalink: /izarra/
---

<a href="https://festivaldelaimagen.com/wp-content/uploads/2021/05/Adina-Izarra-Cornucopia-1024x664.jpg"><img width="512" alt="Photo of Adina Izarra" src="https://festivaldelaimagen.com/wp-content/uploads/2021/05/Adina-Izarra-Cornucopia-1024x664.jpg"></a>


*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Adina_Izarra" target="_blank">https://en.wikipedia.org/wiki/Adina_Izarra</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Izarra, Adina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>