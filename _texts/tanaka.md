---
layout: page
title: Tanaka, Karen (1961-) 
category: incipits
century: 20th
permalink: /tanaka/
---
<a title="DR825, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Karen_Tanaka_(composer)_-_profile.jpg"><img width="256" alt="Karen Tanaka (composer) - profile" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/25/Karen_Tanaka_%28composer%29_-_profile.jpg/256px-Karen_Tanaka_%28composer%29_-_profile.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Karen_Tanaka" target="_blank">https://en.wikipedia.org/wiki/Karen_Tanaka</a>*


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Tanaka, Karen" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
