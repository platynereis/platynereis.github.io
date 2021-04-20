---
layout: page
title: People
permalink: /blog/
---

### Blog

{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{post.title}}</a></li>

{% endfor %}