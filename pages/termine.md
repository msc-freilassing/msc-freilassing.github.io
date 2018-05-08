---
layout: page
show_meta: false
title: "Termine 2018"
subheadline: "Der Terminkalender des MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_8.jpg"
permalink: "/termine/"
---

<ul>
    {% assign sorted = (site.categories.Termine-2018 | sort: 'date') %}
    {% for post in sorted %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
