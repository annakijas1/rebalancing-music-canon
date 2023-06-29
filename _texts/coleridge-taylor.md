---
layout: page
title: Coleridge-Taylor, Samuel (1875-1912)
category: incipits
century: 19th
permalink: /coleridge-taylor/
---

<a title="See file page for creator info." href="https://commons.wikimedia.org/wiki/File:Samuel_Coleridge-Taylor.jpg"><img width="256" alt="Samuel Coleridge-Taylor" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Samuel_Coleridge-Taylor.jpg/256px-Samuel_Coleridge-Taylor.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Samuel_Coleridge-Taylor" target="_blank">https://en.wikipedia.org/wiki/Samuel_Coleridge-Taylor</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Coleridge-Taylor, Samuel" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
