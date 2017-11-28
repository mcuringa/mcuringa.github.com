---
title: "Selected Software Projects::Matthew X. Curinga"
excerpt: "Portfolio of selected software and instructional design projects."
sitemap: true
layout: default
permalink: /software.html
id: software
nav-title: portfolio
order: 30
---

{% assign works = site.portfolio | sort:"work-number" %}


<div class="row">
  <div class="col-4">
      {% for work in works %}
          {% if forloop.index == 1 %}
              <li>active <a href="#">{{work.work-number}} {{work.title}}</a></li>
          {% else %}
              <li><a href="#">{{work.work-number}} {{work.title}}</a></li>
          {% endif %}
      {% endfor %}
  </div>
<div class="col" markdown="0">
{% for work in works %}
<a href="{{work.url}}"><img src="/img/{{work.img}}" alt="{{work.title}}" class="img-fluid">
/img/{{work.img}}</a>
{% endfor %}
</div>

</div>


















