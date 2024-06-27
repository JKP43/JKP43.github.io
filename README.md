# Project Portfolio
Showcasing all of my projects!

---
layout: default
title: "My Portfolio"
---

# My Portfolio

{% for project in site.projects %}
## {{ project.title }}

{{ project.description }}

Read More
{% endfor %}

