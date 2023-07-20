---
layout: page
title: Albert, Adrienne (1941-)
category: incipits
century: 20th
permalink: /albert/
---
*Learn more about this composer at <a href="https://adriennealbert.com" target="_blank">https://adriennealbert.com</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Albert, Adrienne" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>