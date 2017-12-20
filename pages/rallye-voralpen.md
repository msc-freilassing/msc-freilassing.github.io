---
layout: page
show_meta: false
title: "Voralpenrallye"
subheadline: "Die beliebteste Rallye 35 im Voralpenland"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/rallye/voralpen/"
---
Der MSC Freilassing ist Mitglied der Veranstaltergemeinschaft Voralpenrallye. Unsere Mitglieder und ehrenamtlichen Helfer wirken tatkräftig bei der Planung, Organisation und Durchführung mit, um eine der beliebtesten Rallye 35 im Voralpenraum durchführen zu können. Auch Mitglieder des [ISSC][1], mit dem uns seit einigen Jahren eine gute "Freundschaft unter Motorsportverrückten" verbindet, helfen uns bei der Streckensicherung.

[hier][2] geht es zur Hauptseite der Voralpenrallye.



---
### Meldungen zur Voralpenrallye auf msc-freilassing.de:
<ul>
    {% for post in site.categories.Voralpenrallye %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

[1]: http://www.issc-austria.at/
[2]: http://www.voralpenrallye.de/
