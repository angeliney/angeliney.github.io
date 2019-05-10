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
* Machine learning
* Familiarity with reinforcement learning, NLP, computer vision, differential privacy, and causality
* Programming languages: R, Bash shell, Python, Matlab,  Java, C, Racket, Haskell, SQL

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
* Computer Science Undergraduate Committee 2018
* UofT Undergraduate Research in Computer Science Conference 2018 co-chair
* UofT Web Club group leader (2016-2017)
