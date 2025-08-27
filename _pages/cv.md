---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* 2021-now: Research Scientist
  * Transperfect

* 2019-2021: Research Scientist
  * ObeN, Pasadena, USA

* 2016-2018: Research Fellow 
  * Queensland University of Technology

* 2014-2015: Postdoctoral Researcher
  * IDIAP, Switzerland
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
