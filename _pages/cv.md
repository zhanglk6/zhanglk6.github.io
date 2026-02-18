---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interests
======
* Causal inference, adaptive design, precision medicine, semiparametric statistics

Education
======
* PhD in Statistics, Institute of Statistics and Big Data, Renmin University of China, 2021-2026 (expected)
  * Advisor: Dr. Wei Ma
* B.S. in Statistics,  School of Mathematics, Sun Yat-sen University, 2017-2021
  * Advisor: Drs. Hui Huang, Xueqin Wang, Guang Yang
  * GPA: 4.4/5.0 (Ranking: 1/79)
  * 2018 National Scholarship for academic excellence and whole person development (Ranking: 1/231)

Work Experience
======

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
