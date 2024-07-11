---
layout: page
title: Karabyts, Ivan Fedorovych (1945-2002)
category: incipits
century: 20th
permalink: /karabyts/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Karabyts, Ivan Fedorovych" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
