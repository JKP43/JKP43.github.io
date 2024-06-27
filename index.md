---
layout: default
title: "My Portfolio"
---

# My Portfolio

Hello! My name is Jin, and this is my portfolio. Here, you'll find a collection of my projects, along with descriptions and links to the project pages.

{% for project in site.projects %}
- {{ project.title }}

  {{ project.description }}

  Read More
{% endfor %}

