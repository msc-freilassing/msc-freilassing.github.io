---
layout: page
show_meta: false
title: "Termine 2018"
subheadline: "Der Terminkalender des MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_8.jpg"
permalink: "/termine/2018/"
---

<ul>
    {% for post in site.categories.Termine-2018 %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
