---
layout: page
title: Browse by Works for Instrumental - Vocal Chamber Music
permalink: /chamber/
---

<div class="toc">
    
<h3>Instrumental/Vocal Chamber Music</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.ensemble == "chamber-vocal" %}
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
