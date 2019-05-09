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
* B.Sc. Computer Science Specialist, Statistics Minor (GPA: 3.91/4), University of Toronto, 2018
* M.Sc. Computer Science, University of Toronto (projected: 2020)

Work experience
======
  <ul>{% for post in site.work %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Research
======
  <ul>{% for post in site.research %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
