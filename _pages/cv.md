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
* Ph.D Thesis title: "Speech Recognition using Ad-hoc Microphone Arrays", Queensland University of Technology, 2010.
* Master of Project Management, Queensland University of Technology, 2024.
* B.E. in Electrical & Computer Engineering, Queensland University of Technology, 2004.

Work experience
======
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
  
