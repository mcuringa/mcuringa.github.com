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

<div id="portfolio-details" class="col-md-9 col-sm-12" markdown="1">

{% for work in works %}
{% if forloop.index == 1 %}
<div id="work-{{forloop.index}}" class="row port-details active">
{% else %}
<div class="port-details">

{% endif %}

 {{work.content}}
</div>
{% endfor %}


</div>



</div>


