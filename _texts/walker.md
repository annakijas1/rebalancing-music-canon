---
layout: page
title: Walker, Gwyneth (1947-)
category: incipits
century: 20th
permalink: /walker/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Gwyneth_Van_Anden_Walker" target="_blank">https://en.wikipedia.org/wiki/Gwyneth_Van_Anden_Walker</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Walker, Gwyneth" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>