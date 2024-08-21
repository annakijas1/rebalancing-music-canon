---
layout: page
title: Reisserová, Julie (1888-1938)
category: incipits
century: 20th
permalink: /reisserova/
---
<a title="AnonymousUnknown author, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Julie_Reisserova_1931.jpg"><img width="256" alt="Julie Reisserova 1931" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Julie_Reisserova_1931.jpg/256px-Julie_Reisserova_1931.jpg?20100314080225"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Julie_Reisserov%C3%A1" target="_blank">https://en.wikipedia.org/wiki/Julie_Reisserov%C3%A1</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Reisserová, Julie" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
