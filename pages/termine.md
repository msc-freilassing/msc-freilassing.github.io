---
layout: page
show_meta: false
title: "Termine"
subheadline: "Der Terminkalender des MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_8.jpg"
permalink: "/termine/"
---

<div id="calendar"></div>

<ul>
    {% for post in site.categories.Turnier %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
