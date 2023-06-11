layout: page
title: Frank, Gabriela Lena (1972-)
category: incipits
century: 20th
permalink: /frank/


*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Gabriela_Lena_Frank" target="_blank">https://en.wikipedia.org/wiki/Gabriela_Lena_Frank</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Frank, Gabriela Lena" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
