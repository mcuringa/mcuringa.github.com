---
title: "Selected Software Projects::Matthew X. Curinga"
excerpt: "Portfolio of selected software and instructional design projects."
sitemap: true
layout: default
permalink: /software.html
---

Selected Software & Instructional Design
========================================

{% for work in site.software %}
  <h2>{{ work.title }}</h2>
  <p>{{ work.description }}</p>
  <p><a href="{{ work.url }}">{{ work.title }}</a></p>
{% endfor %}





