---
layout: page
title: Leiviskä, Helvi (1902-1982)
category: incipits
century: 20th
permalink: /leiviskä/
---

<a title="Kalle Kultala, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Helvi-Leiviska-1950.jpg"><img width="512" alt="Helvi-Leiviska-1950" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/Helvi-Leiviska-1950.jpg/512px-Helvi-Leiviska-1950.jpg?20201212180429"></a>

*Learn more about this composer at <a href="_blank">https://en.wikipedia.org/wiki/Helvi_Leivisk%C3%A4</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Leiviska, Helvi" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>