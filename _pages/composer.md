---
layout: default
title: Browse by Composer
permalink: /composer/
---
Composer's names appear in alphabetical order and are organized chronologically by century of their birth.

<div class="toc">

<h3>18th century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "18th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

 <h3>19th century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "19th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

  <h3>20th century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "20th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>


</div>
