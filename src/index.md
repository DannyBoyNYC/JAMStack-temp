---
layout: layout.html
pageTitle: New York Today
tags: page
navTitle: Home
---

## Articles

{% for post in collections.post %}

  <h2><a href="{{ post.url }}">{{ post.data.pageTitle }}</a></h2>
  <em>{{ post.date | date: "%Y-%m-%d" }}</em>
{% endfor %}
