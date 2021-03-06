---
title: "PyTutor"
img: /img/portfolio/pytutor/thumb.png
start: 2014
end: 2016
link: https://github.com/mcuringa/py-tutor
work-number: "1"

tags:
- InstructionalDesign
- Python
- Backbone
- Bootstrap
- Javascript
- ComputationalThinking
- p2p
- PeerLearning

---
<div class="row">
  <div class="col-md-5" markdown="1">
[**PyTutor**](https://github.com/mcuringa/py-tutor) is _social tutoring software_ developed as a research experiment for teaching computer programming to novices. It uses community supported learning to present programming challenges in an interactive, online editor.

**Role:** lead developer &amp; instructional designer, PI

  </div>
  <div class="col-md-7" markdown="0">
    <img src="/img/portfolio/pytutor/study.png" class="img-fluid" alt="PyTutor study problem screen">
  </div>
</div>
<br>
**Tags:** {% for tag in page.tags %}<code class="tag">#{{tag}}</code> {% endfor %}
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

