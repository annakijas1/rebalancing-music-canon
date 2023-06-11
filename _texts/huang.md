--- 
layout: page
title: Huang, Ruo (1976-)
category: incipits
century: 20th
permalink: /huang/
---

<a title="CTV Santa Cruz County, CC BY 3.0 &lt;https://creativecommons.org/licenses/by/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Huang_Ruo_at_Meet_the_Composers_2012.jpg"><img width="512" alt="Huang Ruo at Meet the Composers 2012" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Huang_Ruo_at_Meet_the_Composers_2012.jpg/512px-Huang_Ruo_at_Meet_the_Composers_2012.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Huang_Ruo" target="_blank">https://en.wikipedia.org/wiki/Huang_Ruo</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Huang, Ruo" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
