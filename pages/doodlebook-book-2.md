---
layout: page
title: Wupadupa Doodlebook Book 2
description: Comments and doodles in book 2 that capture the essence of each event.
currentPage: doodlebook
permalink: /doodlebook/book-2/index.html
---

<ul class="doodlebook-home-list">
{% for item in site.doodlebook %}
    {% if item.book == 2 %}
  <li>
    <a href="{{ item.permalink }}" class="doodle_thumb">
        <img src="/images/doodlebook/thumbnails/{{ item.linkurl }}" alt="doodle_thumbnail" />
    </a>
  </li>
  {% endif %}  
{% endfor %}
</ul>


