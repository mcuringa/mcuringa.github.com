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
	<!-- <div class="col-md-3 d-md-block d-sm-none"> -->
	<div class="col-md-3">
		<div class="container-fluid">
			<div class="row bg-dark no-gutters">
				{% assign works = site.portfolio | sort:"work-number" %}
				{% for work in works %}
					<div class="col-md-2 port-thumb">
						<a href="#{{work.title}}" onclick="activate({{forloop.index}})">
							<img src="{{work.img}}" alt="{{work.title}}" class="img-fluid">
						</a>
					</div>
				{% endfor %}
			</div> <!-- end thumb row -->
		</div> <!-- end thumb container -->
	</div> <!-- end col 1 -->

	<div id="portfolio-details" class="col-md-9" markdown="0">
		{% for work in works %}
			{% if forloop.index == 1 %}
				<div id="work-{{forloop.index}}" class="port-details active">
			{% else %}
				<div class="port-details">
			{% endif %}

				{{work.content}}
			</div>
		{% endfor %}
	</div>
</div>

<script>
function activate(index) 
{
	$(".port-details").removeClass("active");
	$("#work-" + index).addClass("active");
}
</script>
