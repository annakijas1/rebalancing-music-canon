---
layout: page
title: Browse by Choral Works
permalink: /vocal/
---

<div class="toc">
    
<h3>Choral Music</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.ensemble == "choral" %}
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
