---
layout: page
show_meta: false
title: "Termine"
subheadline: "Der Terminkalender des MSC Freilassing"
header:
   image_fullwidth: "header_unsplash_8.jpg"
permalink: "/termine/"
---

<div id="kronolithCal"></div><script src="https://horde.autogassner.de/services/ajax.php/kronolith/embed?token=lmyfce-2279hmaGPDfxtjA1&amp;calendar=internal_LSwfoPLK1iOqKhYdYH4DYA1&amp;container=kronolithCal&amp;view=month" type="text/javascript"></script>

<ul>
    {% for post in site.categories.Turnier %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
