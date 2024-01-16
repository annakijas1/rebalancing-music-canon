---
layout: page
title: Smith, Linda Catlin (1957-)
category: incipits
century: 20th
permalink: /smith-l/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Linda_Catlin_Smith" target="_blank">https://en.wikipedia.org/wiki/Linda_Catlin_Smith</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Smith, Linda Catlin" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>