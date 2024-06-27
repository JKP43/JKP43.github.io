---
layout: default
title: "My Portfolio"
---

# My Portfolio

Hello! My name is Jin, and this is my portfolio. Here, you'll find a collection of my projects, along with descriptions and links to the project pages.

{% for project in projects %}
<article>
  <h2><a href="/{{ project }}/">{{ project }}</a></h2>
  <p>Description of {{ project }}</p>
  <a href="/{{ project }}/">Read More</a>
</article>
{% endfor %}
