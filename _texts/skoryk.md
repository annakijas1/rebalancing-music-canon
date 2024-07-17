---
layout: page
title: Skoryk, Myroslav (1938-2020)
category: incipits
century: 20th
permalink: /skoryk/
---
<a title="Григорий Ганзбург, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Skoryk3.jpg"><img width="512" alt="Skoryk3" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Skoryk3.jpg/512px-Skoryk3.jpg?20220430212841"></a>
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Myroslav_Skoryk" target="_blank">https://en.wikipedia.org/wiki/Myroslav_Skoryk</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Skoryk, Myroslav" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>