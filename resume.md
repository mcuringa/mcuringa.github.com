---
title: "Resume::Matthew X. Curinga"
excerpt: "The resume Matthew X. Curinga, computer programmer, instructional designer, and software studies researcher."
layout: resume
permalink: /resume.html
id: res
---

<h2 class="mt-0">Goal</h2>
A senior level technical position where I use my experience building and researching software systems to help create technologies that serve the public good.

Relevant Experience
-------------------
<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>2010-present</strong>
    <div class="text-muted">New York</div>
  </div>
<div class="col" markdown="1">
**[Adelphi University](http://education.adelphi.edu/)**<br>
**Associate Professor**

Tenured faculty teaches courses in computer science, instructional design, human cognition, digital communications, and multimedia production. Co-designed new graduate programs: PhD in Learning Sciences, MA in Computer Science Education, and 100% online MA in Educational Technology. Co-founded the [MIXI research and practice institute](https://mixi.nyc). Research examines social and economic impact of software and digital systems. Track record of designing and building novel software platforms for research purposes.
</div>
</div>

<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>2009-2010</strong>
    <div class="text-muted">New York, NY</div>
  </div>
<div class="col" markdown="1">
**[Brainscape](http://brainscape.com/)**<br>
**Lead Software Developer**

Software architect and first programmer for this ed tech start-up focused on study tools. Developed the original Java-based web and mobile code and coordinated teams of remote developers in the U.S. and India.
</div>
</div>

<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>2002-2008</strong>
    <div class="text-muted">New York, NY</div>
  </div>
<div class="col" markdown="1">
**[Nielsen / IAG Research](https://www.nielsen.com/)**<br>
**Lead Programmer, Web Applications**

Led team of 20+ programmers, designers, database administrators, and sys admins. Implemented test-driven and agile software development procedures. Established practices to mentor new software developers and to create a learning community among the entire team. As lead developer of web applications, designed and coded scalable, redundant, high traffic Java-based web application which served hundreds of thousands of unique users with traffic greater than 10M visits a day. Oversaw team development of custom data tools for both collecting and analyzing data.
</div>
</div>

<p class="break">&nbsp;</p>

<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>1999-2002</strong>
    <div class="text-muted">New York, NY</div>
  </div>
<div class="col" markdown="1">
**Crisp Wireless**<br>
**Co-founder, Chief Technical Officer**

Co-founded one of the first companies building software for Java-enabled phones, worked as the principle architect of a mobile client-server content management system that introduced some of the first social media content to mobile platforms; powering fan apps for artists like Christina Aguilera. Successfully led search for venture funding and clients that resulted in Crisp's eventual acquisition.
</div>
</div>



<h2 class="">Education</h2>
{% for school in site.data.education %}
<div class="row" markdown="0">
<div class="col-3 text-end">

<strong>{{school.date}}</strong>
<div class="text-muted">{{school.place}}</div>
</div>
<div class="col" markdown="1">
<strong markdown="1">[{{school.school}}]({{school.link}})</strong><br>
<strong>{{school.degree}}</strong><br>{{school.note}}
</div>
</div>
{% endfor %}

<div class="ref" markdown="1">

Selected Papers & Talks
-----------------------
<div class="row">
<div class="col-3 text-end">
<i class="bi bi-easel2 fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**Protocol: A Constructionist game for teaching computing and adapted design in the Maker Lab.** _The 2023 Annual Meeting of the American Education Research Association_, Chicago, IL.
</div>
</div>

<div class="row">
<div class="col-3 text-end">
<i class="bi bi-easel2 fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**Video games for learning in computer science education.** _British Educational Research Association (BERA) Annual Conference 2018_. Northumbria University, Newcastle, England.
</div>
</div>

<div class="row">
<div class="col-3 text-end">
<i class="bi bi-journal-text fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**[The MOOC and the Multitude](http://dx.doi.org/10.1111/edth.12171).** _Educational Theory_, _66_(3), 369–387.
</div>
</div>

<div class="row">
<div class="col-3 text-end">
<i class="bi bi-journal-text fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**[Mobile First Instructional Design](https://amzn.com/1522502513).** In D. Mentor (Ed.), _Handbook of Research on Mobile Learning in Contemporary Classrooms_. IGI Global.
</div>
</div>

<div class="row">
<div class="col-3 text-end">
<i class="bi bi-journal-text fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**[Critical analysis of interactive media with software affordances](http://firstmonday.org/ojs/index.php/fm/article/view/4757).** _First Monday_, _19_(9).
</div>
</div>

<div class="row">
<div class="col-3 text-end">
<i class="bi bi-easel2 fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**Networks, design, and solidarity.** _The Twelfth Annual Meeting of the Cultural Studies Association (US)_, Salt Lake City.
</div>
</div>

<div class="row">
<p class="break">&nbsp;</p>
<div class="col-3 text-end">
<i class="bi bi-journal-text fs-4"></i>
</div>
<div class="col align-left" markdown="1">
**Wikiotics: the interactive language instruction Wiki.** _Proceedings of the 7th International Symposium on Wikis and Open Collaboration_ (pp. 223–224).
</div>
</div>
</div>

<h2 class="">Awards & Honors</h2>
<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>2020</strong>
  </div>
  <div class="col">
    <strong markdown="1">National Science Foundation I-Corps</strong>
    <div class="text-muted mb-2">Part of team of 3-person "BLAST bilingual learning software" team selected for NSF "start-up" funding of $50,000</div>
  </div>
</div>

{% for award in site.data.awards %}
<div class="row" markdown="0">
  <div class="col-3 text-end">
    <strong>{{award.date}}</strong>
  </div>
  <div class="col">
    <strong markdown="1">{{award.title}}</strong>
    <div class="text-muted mb-2">{{award.note}}</div>
  </div>
</div>
{% endfor %}
