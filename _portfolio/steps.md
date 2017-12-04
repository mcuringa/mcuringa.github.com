---
title: "STEPS"
img: /img/portfolio/steps/thumb.png
link: ""
work-number: "15"
tags: 
  - Python 
  - Case Based Learning 
  - bilingual
  - biliteracy
  - Javascript 
  - research
---
<div class="row">
  <div class="col-md-5" markdown="1">
The **Steps-to-literacy** project investigates the ways that multimedia anchors and purposefully designed software can support the English academic writing of Spanish-English emergent bilingual students. As part a graduate student researcher, I was part of the initial team that created the experimental design to test a novel writing scaffold (STEPS+G) and to create and test new writing software. I was the lead (and sole) software developer on the project, as well as the instructor for a series of 15+ trial teaching sessions with Spanish speaking 8th grade students in the Bronx, NY.

**Role:** lead developer,instructional designer, graduate research assistant

**Tags:** {% for tag in page.tags %}<code class="tag">#{{tag}}</code> {% endfor %}
  </div>
  <div class="col-md-7" markdown="0">
    <img src="/img/portfolio/steps/skin.png" class="img-fluid" alt="PyTutor study problem screen">
  </div>
</div>
<br>

<div class="row">

{% capture desc %}
The integrated note taker helped students gather evidence for their essays.
{% endcapture %}

{% include card.html 
  id="note-taker" img="/img/portfolio/steps/note-taker.png" 
  alt="steps note taker" 
  content=desc %}


{% capture desc %}
Students used evidence gathered in the lesson to repsond to writing prompts. Materials and notes were presented in Spanish and English, but formal writing was written in English.
{% endcapture %}

{% include card.html 
  id="steps-essay" img="/img/portfolio/steps/essay.png" 
  alt="steps writing prompts" 
  content=desc %}


{% capture desc %}
Built-in language tools worked to reduce cognitive load in working with multilingual materials, helping students focus on the tasks of reading and writing academic work.
{% endcapture %}

{% include card.html 
  id="lang-tool" img="/img/portfolio/steps/lang-tool.png" 
  alt="language tools" 
  content=desc %}
  
</div>