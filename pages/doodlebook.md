---
layout: page
title: Wupadupa Doodlebook - home
description: Comments and doodles that capture the essence of each event.
currentPage: doodlebook
permalink: /doodlebook/index.html
---

Welcome to the strange and wonderful world of the Wupadupa doodlebook.

At every Wupadupa gig the doodlebook is passed around for members of the audience to sign, leave comments in and draw the odd doodle in. The comments and doodles capture the essence of each gig and range from the deeply personal to the rather weird! We regularly post the best ones on here on the site where you can both view and leave comments about them.

To begin choose a book below.

{% assign book1 = site.doodlebook | where:"book", 1 | first %}
{% assign book2 = site.doodlebook | where:"book", 2 | first %}
{% assign book3 = site.doodlebook | where:"book", 3 | first %}
{% assign book4 = site.doodlebook | where:"book", 4 | first %}
{% assign book5 = site.doodlebook | where:"book", 5 | first %}

<a href="book-1/doodle-{{ book1.ref }}.html" class="doodlebook_cover book1">Book 1</a>
<a href="book-2/doodle-{{ book2.ref }}.html" class="doodlebook_cover book2">Book 2</a>
<a href="book-3/doodle-{{ book3.ref }}.html" class="doodlebook_cover book3">Book 3</a>
<a href="book-4/doodle-{{ book4.ref }}.html" class="doodlebook_cover book4">Book 4</a>
<a href="book-5/doodle-{{ book5.ref }}.html" class="doodlebook_cover book5">Book 5</a>