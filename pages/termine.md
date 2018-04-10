---
layout: page
show_meta: false
title: "Termine"
subheadline: "Der Terminkalender des MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_8.jpg"
permalink: "/termine/"
---

<ul>
    {% for post in site.categories.Turnier %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
