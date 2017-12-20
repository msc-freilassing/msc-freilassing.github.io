---
layout: page
show_meta: false
title: "Rallye-Sprint MSC Freilassing"
subheadline: "Alles zu unseren Rallye-Sprints"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/rallye/sprint/"
---
<ul>
    {% for post in site.categories.Sprint %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
