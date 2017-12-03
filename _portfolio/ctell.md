---
title: "CTELL"
img: "/img/portfolio/ctell/thumb.png"
start: 2008
end: 2010
work-number: "10"
link: ""
tags:
  - case-based learning
  - instructional design
  - Java/J2EE
  - Javascript
  - jQuery
  - literacy

---
<div class="row">
  <div class="col-md-5" markdown="1">
[**CTELL**](http://ctell.uconn.edu/home.htm) is web-based software for teacher literacy education
that integrates **case-based learning** and multimedia **anhcored instruction.** I was the lead software engineer for version 2 of the software, porting it from a desktop application to a cloud-based web application.  I also designed version 2 to be a full-fledged case learning authoring tool that worked independently of the initial literacy education domain.

**Role:** lead software engineer

**Tags:** {% for tag in page.tags %}<span class="tag type-code">#{{tag}}</span> {% endfor %}
  </div>
  <div class="col-md-7" markdown="0">
    <img src="/img/portfolio/ctell/ctell-home.png" class="img-fluid" alt="ctell list of literacy cases">
  </div>
</div>

<div class="row">

{% capture desc %}
Our <code>wiki-like question editor</code> with test-driven question validation allows many people to collaborate to write high-quality question prompts.
{% endcapture %}

{% include card.html 
  id="pytutor1" img="/img/portfolio/pytutor/wiki.png" 
  alt="wiki question editor" 
  content=desc %}


{% capture desc %}
<em>Programming is a creative process!</em> Learners study <code>solutions</code> written by others to learn new ways to solve problems.
{% endcapture %}

{% include card.html 
  id="pytutor2" img="/img/portfolio/pytutor/code.png" 
  alt="peer code solutions" 
  content=desc %}


{% capture desc %}
PyTutor incorporates features from <code>social networks</code> to make it
easy to ask friends for a little help if you get stuck. Nobody (including
instructors), can look at your code or the number of attempts you get right or
wrong.
{% endcapture %}

{% include card.html 
  id="pytutor3" 
  img="/img/portfolio/pytutor/add-friend.png" 
  alt="social profile" 
  content=desc %}

</div>

{% include modal.html 
  title="question editor"
  id="pytutor1" img="/img/portfolio/pytutor/wiki.png" 
  alt="wiki question editor" %}

{% include modal.html 
  title="peer solutions"
  id="pytutor2" 
  img="/img/portfolio/pytutor/code.png" 
  alt="wiki question editor" %}

{% include modal.html 
  title="social profile"
  id="pytutor3" 
  img="/img/portfolio/pytutor/add-friend.png" 
  alt="social profile" %}




