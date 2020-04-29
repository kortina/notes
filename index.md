---
layout: default
title: 'Notes -- Andrew Kortina'
---

Notes on books / essays / films / etc...

---

{% for post in site.posts %}<p><a href="{{site.url}}{{ post.url }}">{{ post.title }}</a></p>{% endfor %}