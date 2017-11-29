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

<div class="row" markdown="0">

<div class="col-md-3 col-sm-12">

<div class="container-fluid">
<div class="row bg-dark no-gutters">

{% assign works = site.portfolio | sort:"work-number" %}
{% for work in works %}
<div class="col-6 port-thumb">
	<a href="{{work.url}}">
		<img src="{{work.img}}" alt="{{work.title}}" class="img-fluid">
	</a>
</div>
{% endfor %}

</div> <!-- end thumb row -->
</div> <!-- end thumb container -->

</div> <!-- end col 1 -->

<div class="col-md-9 col-sm-12" markdown="1">

**PyTutor** is `social tutoring software` to help you learn the basics 
of programming in Python. We believe in community-supported learning and collaboration when learning to code. Solve programming challenges from our web-based interactive editor.


</div>



</div>


