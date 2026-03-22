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
* M.S. in Information Science and Electronic Engineering, Zhejiang University, 2024 (present)
  * College of Information Science and Electronic Engineering
  * Research: Computer Vision, Multimodal Learning, Large Models
* B.S. in Electronic Information Engineering, Jilin University, 2023
  * State Key Laboratory on Integrated Optoelectronics

Research Interests
======
* Computer Vision
* Multimodal Learning
* Large Language Models
* Deep Learning on Large Datasets

Skills
======
* Programming Languages: Python, C++, MATLAB
* Deep Learning Frameworks: PyTorch, TensorFlow, Keras
* Computer Vision: OpenCV, PIL, Image Processing
* Tools & Platforms: Git, Docker, Linux, Jupyter
* Languages: Chinese (Native), English (Professional)

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
  
Service and leadership
======
* Reviewer for academic conferences and journals
