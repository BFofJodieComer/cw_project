---
title: Gallery index
layout: index
---

(% for exhibit in site.exhibits %)

<img scr="{{ exhibit.image.url }}" width = 256>
<p> {{ exhibits.title }} by {{ exhibits.creator }} </p>
<p><a> href="{{ exhibit.licence.url }}"> {{ exhibits.licence }}</a></p>

(% endfor %)
