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
* **B.S. in Computer Science**, Beihang University, July 2024 - Present
  * GPA: 3.92/4.00, Rank: No.1
  * Relevant Coursework: Computer Organization, Machine Learning

* **B.S. in Aeronautic Science and Engineering**, Beihang University, September 2022 - July 2024
  * GPA: 3.90/4.00, Rank: No.1
  * Relevant Coursework: C Language Programming, Fundamentals of Data Structures and Algorithms

Work Experience
======
* **Research Intern**, November 2024 - Present
  * Colalab, Beijing, China
  * Algorithm optimization works on specific purposes
  * Working on a satellite simulation platform based on PyTorch

* **Head of On-board-computer Research Team**, October 2023 - October 2024
  * CubeSat Team of School of Astronautics, Beihang University, Beijing, China
  * Published articles at domestic and international aerospace conferences
  * Collaborated with doctoral students in the laboratory on various tasks
  * Guided students of the 2021 class of the School of Astronautics to intern

Skills
======
* **Programming Languages**
  * C, C++, Python, Java
  * Cmake, Verilog, TeX, Fortran
* **Technologies & Frameworks**
  * PyTorch, TensorFlow, Scikit-learn
  * ROS2
  * Git, Nginx
* **Areas of Expertise**
  * Embedded Systems Development
  * Machine Learning
  * Satellite Systems and Flight Software

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

Awards
======
  <ul>{% for post in site.awards reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
