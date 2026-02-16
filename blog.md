---
layout: default
title: Writing
permalink: /blog/
---

## Technical Writing

{% for post in site.posts %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}
