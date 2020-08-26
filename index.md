---
layout: default
title: 'Notes -- Andrew Kortina'
---

Notes on books / essays / films / etc...

---

{% assign posts = site.n | sort: 'date' | reverse %}{% for post in posts %}<p><a href="{{site.url}}{{ post.url }}">{{ post.title }}</a></p>{% endfor %}
