---
layout: default
title: Browse by Band Music
permalink: /band/
---

<div class="toc">
   
 <h3>Music for Band</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.ensemble == "band" %}
          <li class="text-author.text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.author }} -
         {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
  </ul>
    
</div>
