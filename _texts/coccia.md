---
layout: page
title: Coccia, Maria Rosa (1759-1833)
category: incipits
century: 18th
permalink: /coccia/
---
<a title="Attributed to Antonio Cavallucci, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:M._R._Coccia.jpg"><img width="256" alt="M. R. Coccia" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/M._R._Coccia.jpg/256px-M._R._Coccia.jpg?20130411122342"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Maria_Rosa_Coccia" target="_blank">https://en.wikipedia.org/wiki/Maria_Rosa_Coccia</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Coccia, Maria Rosa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
