---
layout: page
title: Archer, Violet (1913-2000)
category: incipits
century: 20th
permalink: /archer/
---

<a title="Archer, Violet (1913-2000), Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Violet_Archer_on_graduation_day,_Yale_University.tif"><img width="256" alt="Violet Archer on graduation day, Yale University" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Violet_Archer_on_graduation_day%2C_Yale_University.tif/lossy-page1-430px-Violet_Archer_on_graduation_day%2C_Yale_University.tif.jpg"></a>
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Violet_Archer" target="_blank">https://en.wikipedia.org/wiki/Violet_Archer</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Archer, Violet" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
