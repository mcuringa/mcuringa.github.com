---
title: "Selected Software Projects::Matthew X. Curinga"
excerpt: "Portfolio of selected software and instructional design projects."
sitemap: true
layout: portfolio
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
					<div id="thumb-{{forloop.index}}" class="col-md-6 port-thumb">
						<a href="#{{work.title}}" onclick="activate({{forloop.index}})">
							<div class="port-title text-center">{{work.title}}</div>
              <img src="{{work.img}}" alt="{{work.title}}" class="img-fluid">
						</a>
					</div>
				{% endfor %}
			</div> <!-- end thumb row -->
		</div> <!-- end thumb container -->
	</div> <!-- end col 1 -->

	<div id="portfolio-details" class="col-md-9" markdown="0">
		{% for work in works %}
				<div id="work-{{forloop.index}}" class="port-details">
				{{work.content}}
			</div>
		{% endfor %}
	</div>
</div>

<script>
let workMap = {
  "": 1,

{% for work in works %}
"#{{work.title}}": {{forloop.index}},
{% endfor %}
};

function activate(index) 
{
	$(".port-details").removeClass("active");
	$("#work-" + index).addClass("active");
	$(".port-thumb").removeClass("active");
	$("#thumb-" + index).addClass("active");
}

window.onload = ()=> {
    let work = window.location.hash;
    console.log(work);
    console.log(workMap[work]);
    activate(workMap[work]);
};
</script>
