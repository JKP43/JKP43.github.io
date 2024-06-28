---
layout: default
---

# My Portfolio

Hello! My name is Jin, and this is my portfolio. Here, you'll find a collection of my projects, along with descriptions and links to the project pages.

{% for project in site.projects %}
<article>
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  <p>{{ project.description }}</p>
  <a href="{{ project.url }}">Read More</a>
</article>
{% endfor %}
