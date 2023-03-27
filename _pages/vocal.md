---
layout: page
title: Browse by Vocal Works
permalink: /vocal/
---

<div class="toc">
    
<h3>Vocal Music</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.ensemble == "vocal" %}
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
