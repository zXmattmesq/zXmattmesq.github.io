---
layout: default
title: Projects
---

# Projects

Here are some of my notable projects:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

[Back to Home](index.md)
