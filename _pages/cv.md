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
* Ph.D in Computer Architecture, Beihang University, 2022
* M.S. in Computer Science and Technology, Zhengzhou University, 2017
* B.S. in Computer Science and Technology, Zhengzhou University, 2014

Work experience
======
* January 2025 -- present: Lecturer 
  * University of Science and Technology Beijing
  * Duties: conduct research in medical image analysis, applicate grants, mentor undergraduate students


* September 2022 -- December 2024: Postdoctoral Researcher
  * University of Science and Technology Beijing
  * Duties: conduct research in medical image analysis, applicate grants, mentor undergraduate students
  
Skills
======
* Programming: Python (PyTorch), MATLAB
* Tools: Linux, Git, Docker, LaTeX
* Languages: English (Fluent), Chinese (Native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
  <ul>{% for post in site.portfolio reversed %}
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
  
Service and leadership
======
* Reviewer for IEEE TSMC-A (2024), Scientific Reports (2024, 2025)
