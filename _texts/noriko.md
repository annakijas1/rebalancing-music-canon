---
layout: page
title: Noriko, Baba (1972-)
category: incipits
century: 20th
permalink: /noriko/
---

*Learn more about this composer at <a href="https://brahms.ircam.fr/en/noriko-baba" target="_blank">https://brahms.ircam.fr/en/noriko-baba</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Noriko, Baba" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
