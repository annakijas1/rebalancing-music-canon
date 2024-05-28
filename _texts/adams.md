---
layout: page
title: Adams, Leslie (1932-2024)
category: incipits
century: 20th
permalink: /adams/
---
<a title="Michael Dalby, CC BY 3.0 &lt;https://creativecommons.org/licenses/by/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:H_leslie_adams.jpg"><img width="256" alt="H leslie adams" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/H_leslie_adams.jpg/256px-H_leslie_adams.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Leslie_Adams_(composer)" target="_blank">https://en.wikipedia.org/wiki/Leslie_Adams_(composer)</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Adams, Leslie" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
