---
title: "Curriculum Vitae::Matthew X. Curinga"
excerpt: "The academic CV of Matthew X. Curinga, computer programmer, instructional designer, and software studies researcher."
sitemap: true
layout: default
permalink: /cv-short.html
id: cv-short
order: 20
---


<header id="" class="text-right" markdown="0">
<div class="text-right">
<strong>Matthew X. Curinga</strong>
</div>
<div class="contact text-right text-muted">
  <a href="mailto:mcuringa@adelphi.edu" class="text-muted">mcuringa@adelphi.edu</a><br>
  <a href="https://matt.curinga.com" title="go to the personal website of matt curinga" class="text-muted">https://matt.curinga.com</a><br>
  <a href="https://github.com/mcuringa" title="github repos" class="text-muted">https://github.com/mcuringa</a><br>
</div>
</header>
<h1 class="text-center">Curriculum Vitae</h1>

Education
---------

{% for school in site.data.education %}
<div class="row" markdown="0">
<div class="col-3 text-right">

<strong>{{school.date}}</strong>
<div class="text-muted">{{school.place}}</div>
</div>
<div class="col" markdown="1">
<strong markdown="1">[{{school.school}}]({{school.link}})</strong><br>
<strong>{{school.degree}}</strong><br>{{school.note}}
</div>
</div>
{% endfor %}



Academic positions
------------------
<div class="row" markdown="0">
  <div class="col-3 text-right">
    <strong>2010-present</strong>
    <div class="text-muted">New York</div>
  </div>
<div class="col" markdown="1">
**[Adelphi University](http://education.adelphi.edu/)**  
Program in Educational Technology, College of Education and Health Sciences
Associate Professor, 2016-present  
Program Director, 2011-2014, 2016-present  
Assistant Professor, 2010-2016  
</div>
</div>

<div class="row" markdown="0">
  <div class="col-3 text-right">
    <strong>2001, 2007-08</strong>
    <div class="text-muted">New York, NY</div>
  </div>
<div class="col" markdown="1">
**[Teachers College Columbia University](http://www.tc.columbia.edu)**  
Adjunct Instructor
</div>
</div>


<div class="ref" markdown="1">

Selected articles & chapters
----------------------------

**Curinga, M.** (2016). [The MOOC and the Multitude](http://dx.doi.org/10.1111/edth.12171). _Educational Theory_, _66_(3), 369–387.

**Curinga, M.**, & Saravanos, A. (2016). [Mobile First Instructional Design](https://amzn.com/1522502513). In D. Mentor (Ed.), _Handbook of Research on Mobile Learning in Contemporary Classrooms_. IGI Global.

De Freitas, E., & **Curinga, M.** (2015). [New materialist approaches to the study of language and identity: Assembling the posthuman subject](http://doi.org/10.1080/03626784.2015.1031059). _Curriculum Inquiry_, _45_(3), 249–265.

**Curinga, M.**, & Auchter, K. (2015). [Designing PyTutor: A Social Tutor to Support Computer Science Education Through Collaborative Study](https://www.isls.org/cscl2015/papers/CSCL2015ProceedingsVolume2.pdf). In Lindwall, P. Häkkinen, T. Koschman, P. Tchounikine, & S. Ludvigsen (Eds.), _Exploring the Material Conditions of Learning: The Computer Supported Collaborative Learning (CSCL) Conference 2015_ (Vol. 2, pp. 833–834). Gothenburg, Sweden: _The International Society of the Learning Sciences_.

**Curinga, M.** (2014). [Critical analysis of interactive media with software affordances](http://firstmonday.org/ojs/index.php/fm/article/view/4757). _First Monday_, _19_(9).

Sullivan, I., Garrison, J. R., & **Curinga, M.** (2011). Wikiotics: the interactive language instruction Wiki. _Proceedings of the 7th International Symposium on Wikis and Open Collaboration_ (pp. 223–224).


Selected Presentations
------------------------------------------
**Curinga, M.** (2018). Video games for learning in computer science education. _British Educational Research Association (BERA) Annula Conference 2018_. Northumbria University, Newcastle, England, September 11-13, 2018.

Carlin, M., & **Curinga, M.** (2017). Educating against capitalism and corporatization through cooperative schooling. Presented at _Marx's Critique of Political Economy and the Global Crisis Today: On the 150th Anniversary of the Publication of Capital_, Hofstra University, New York.

**Curinga, M.** (2014). Networks, design, and solidarity. _The Twelfth Annual Meeting of the Cultural Studies Association (US)_, Salt Lake City, May 29-31, 2014.

**Curinga, M.** (2012). To know is not important: Ivan Illich and Jacques Rancière's relational pedagogy. Presented at _The 2012 Annual Meeting of the American Education Research Association_, Vancouver, Canada.

**Curinga, M.** (2011). Building the learning commons: education as the work of producing open learning materials. _Mobility shifts: an international future of learning summit_. The New School, New York, October 10-16, 2011.

Saravanos, A., & **Curinga, M.** Lessons learned from using a wiki as a course management system. Presented at _The 41st ACM Technical Symposium on Computer Science Education (SIGCSE)_. Milwaukee, WI, USA, March 10-13, 2010.

**Curinga, M.** (2009) Wikipedia and Jacques Rancière's philosophy of radical equality. _Proceedings of Wikimania 2009, academic track_.

Kleifgen, J., **Curinga, M.**, and Kaun, K. (2008) STEPS to literacy for emergent bilinguals: integrating web-based and curricular support for Latino middle-school writers. _American Anthropological Association Annual Meeting 2008_. San Francisco.

</div>

Grants & Funded Research
-------------------------------

{% for work in site.data.grants %}
<div class="row" markdown="0">
<div class="col-3 text-right">
<strong>{{work.date}}</strong>
<div class="text-muted">{{work.amount}}<p>{{work.funded}}</p></div>
</div>
<div class="col" markdown="1">
<strong>{{work.title}}</strong>  
_{{work.inst}}_  
{{work.researchers}}
</div>
</div>
{% endfor %}

Awards & Honors
---------------

{% for award in site.data.awards %}
<div class="row" markdown="0">
  <div class="col-3 text-right">
    <strong>{{award.date}}</strong>
  </div>
  <div class="col">
    <strong markdown="1">{{award.title}}</strong>
    <p class="text-muted">{{award.note}}</p>
  </div>
</div>
{% endfor %}

K-12 Education Teaching Experience
------------------------------------
{% for work in site.data.teaching %}
<div class="row" markdown="0">
<div class="col-3 text-right">
<strong>{{work.date}}</strong>
<p class="text-muted">{{work.place}}</p>
</div>
<div class="col" markdown="1">
<strong>{{work.title}}</strong>  
{{work.job}}  
</div>
</div>
{% endfor %}

Professional Software Development Experience
--------------------------------------------
{% for work in site.data.work %}
<div class="row" markdown="0">
<div class="col-3 text-right">
<strong>{{work.date}}</strong>
<div class="text-muted">{{work.place}}</div>
</div>
<div class="col" markdown="1">
<strong>{{work.title}}</strong>  
{{work.job}}  
</div>
</div>
{% endfor %}
