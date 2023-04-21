---
layout: page
title: Arismendi, Diana (1962-)
category: incipits
century: 20th
permalink: /arismendi/
---

<a title="A. Rugeles, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Arismendi,_foto.jpg"><img width="256" alt="Arismendi, foto" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Arismendi%2C_foto.jpg/512px-Arismendi%2C_foto.jpg"></a>
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Diana_Arismendi" target="_blank">https://en.wikipedia.org/wiki/Diana_Arismendi</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Arismendi, Diana" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
