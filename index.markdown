---
layout: page
permalink: /home/
---

The marine annelid *Platynereis dumerilii* is an

## Blog

{% for post in site.posts %} 
  <li><a href="{{ post.url }}">{{post.title}}</a></li>

{% endfor %}