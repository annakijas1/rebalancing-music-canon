---
layout: page
title: Assad, Clarice (1978-)
category: incipits
century: 20th 
permalink: /assad/
---
//if the composer has a wikipedia page and there is an image, click on the image and then more details to view the file. Go to "use this file on the web" to view the embed code and then insert it below//

//insert embed code to public domain image here, if available//

*Learn more about this composer at <a href="https://clariceassad.com/" target="_blank">https://clariceassad.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Assad, Clarice" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>