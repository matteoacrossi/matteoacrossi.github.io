---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Physics, Università degli Studi di Milano (2017) 
  Supervisor: Prof. Matteo G. A. Paris
* M.S. in Physics cum laude, Università degli Studi di Parma (2014)
* B.S. in Physics cum laude, Università degli Studi di Parma (2012)

Work experience
======
* Senior researcher, University of Turku (Nov 2017- July 2018)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   