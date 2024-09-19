---
layout: default
title: Projects
---

# Projects

Personal and Professional Projects:


{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
