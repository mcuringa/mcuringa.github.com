---
title: "Selected Software Projects::Matthew X. Curinga"
excerpt: "Portfolio of selected software and instructional design projects."
sitemap: true
layout: default
permalink: /software.html
id: software
nav-title: portfolio
order: 30
cards:
  - title: nycschools
    thumb: /img/portfolio/nycschools/thumb.png
    alt: nyc schools open data
    desc: Free Open Source Software library for open school data
    link: https://adelphi-ed-tech.github.io/nycschools/
  - title: PyTutor
    thumb: /img/portfolio/pytutor/thumb.png
    desc: Social tutoring platform for studying computer science
    link: /software/pytutor.html
  - title: Wordpress
    thumb: /img/portfolio/wp/thumb.png
    desc: Wordpress info design, themes, and plug-ins
    link: /software/wordpress.html
  - title: STEPS to Literacy
    thumb: /img/portfolio/steps/thumb.png
    desc: Bilingual writing platform for critical literacy
    link: /software/steps.html
  - title: Brainscape
    thumb: /img/portfolio/brainscape/thumb.png
    desc: Brainscape mobile flash cards for Android and iOS
    link: /software/brainscape.html
  - title: RewardTV
    thumb: /img/portfolio/rtv/thumb.png
    desc: Gamification website to survey media viewing habits
    link: /software/rtv.html
---
<h1>selected software and instructional design projects</h1>


<div id="ProjectGallery" class="container">
    <div class="row">
    {% for card in page.cards %}
        <div class="col-md-4 col-sm-1">
            <div class="card">
                <img src="{{card.thumb}}" class="card-img-top" alt="{{card.alt}}">
                <div class="card-body">
                    <h5 class="card-title">{{card.title}}</h5>
                    <p class="card-text">{{card.desc}}</p>
                    <a href="{{card.link}}" class="btn btn-primary">Read More</a>
                </div>
            </div>
        </div>
    {% endfor %}
    </div>
</div>


