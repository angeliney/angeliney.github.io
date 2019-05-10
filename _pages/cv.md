---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Please find my cv here](https://docs.google.com/document/d/1ldxzTx0Db_mLOzj0t0Nw06v3kF7Z-87UPAZypNGwcZw/edit?usp=sharing)

Education
======
* B.Sc. Computer Science Specialist, Statistics Minor (GPA: 3.91/4), University of Toronto, 2018
* M.Sc. Computer Science, University of Toronto (projected: 2020)

Work experience
======
  <ul>{% for post in site.work reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Machine learning
* Familiarity with reinforcement learning, NLP, computer vision, differential privacy, and causality
* Programming languages: R, Bash shell, Python, Matlab,  Java, C, Racket, Haskell, SQL

Papers/posters
======
  <ul>{% for post in site.research reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Computer Science Undergraduate Committee 2018
* UofT Undergraduate Research in Computer Science Conference 2018 co-chair
* UofT Web Club group leader (2016-2017)
