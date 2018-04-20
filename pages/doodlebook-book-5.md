---
layout: page
title: Wupadupa Doodlebook Book 5
description: Comments and doodles in book 5 that capture the essence of each event.
currentPage: doodlebook
permalink: /doodlebook/book-5/index.html
---

<ul class="doodlebook-home-list">
{% for item in site.doodlebook %}
    {% if item.book == 5 %}
  <li>
    <a href="{{ item.permalink }}" class="doodle_thumb">
        <img src="/images/doodlebook/thumbnails/{{ item.linkurl }}" alt="doodle_thumbnail" />
    </a>
  </li>
  {% endif %}  
{% endfor %}
</ul>


