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
* Causal inference, adaptive design, machine learning methods, precision medicine

Education
======
* Ph.D in Statistics, Institute of Statistics and Big Data, Renmin University of China, 2021-2026 (expected)
  * Advisor: Drs. Wei Ma, Zheng Zhang, Yang Liu, Feifang Hu
  * Performed preliminary reviews for manuscripts submitted to Statistica Sinica,
    Statistics in Medicine, and Statistical Methods in Medical Research
* B.S. in Statistics,  School of Mathematics, Sun Yat-sen University, 2017-2021
  * Advisor: Drs. Hui Huang, Xueqin Wang, Guang Yang
  * GPA: 4.0/4.0 (Ranking: 1/79)
  * 2018 National Scholarship for academic excellence and whole person development (Ranking: 1/231)

Work experience
======
* Quant: Quantitative Investment Research With Machine Learning
  * Simulated stock price prediction strategies with machine learning methods 

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
