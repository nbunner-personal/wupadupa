---
layout: page
title: Wupadupa Doodlebook Book 4
description: Comments and doodles in book 4 that capture the essence of each event.
currentPage: doodlebook
permalink: /doodlebook/book-4/index.html
---

<ul class="doodlebook-home-list">
{% for item in site.doodlebook %}
    {% if item.book == 4 %}
  <li>
    <a href="{{ item.permalink }}" class="doodle_thumb">
        <img src="/images/doodlebook/thumbnails/{{ item.linkurl }}" alt="doodle_thumbnail" />
    </a>
  </li>
  {% endif %}  
{% endfor %}
</ul>


