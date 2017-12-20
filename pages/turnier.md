---
layout: page
show_meta: false
title: "Automobilturnier"
subheadline: "Lizenzfreier Motorsport beim beim MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/turnier/"
---
<ul>
    {% for post in site.categories.Turnier %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
