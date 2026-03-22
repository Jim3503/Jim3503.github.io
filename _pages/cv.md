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
* **M.S.** in Information Science and Electronic Engineering, Zhejiang University, 2024–present
  * College of Information Science and Electronic Engineering
  * Research Focus: Computer Vision, Multimodal Learning, Large Models
  * **Achievements**: Published 1 paper (1st author, international conference); 1 CCF-A journal paper under review; 1 authorized patent

* **B.S.** in Electronic Information Engineering, Jilin University, 2020–2024
  * State Key Laboratory on Integrated Optoelectronics, School of Electronic Science and Engineering
  * **Awards**:
    - First Prize, National Undergraduate Mathematics Competition (Provincial Level)
    - Second Prize, National Undergraduate Electronic Design Competition (Provincial Level)
    - Second-Class Scholarship, Jilin University
    - Outstanding Student, College Level

Research Interests
======
* Computer Vision: Image recognition, object detection, visual understanding
* Multimodal Learning: Vision-language models, cross-modal learning, Sign Language Translation
* Large Language Models: Training and fine-tuning large-scale models, RAG, Agent Systems
* Deep Learning: Efficient training methods for large-scale datasets, Knowledge Distillation

Skills
======
* **Programming Languages**: Python, C++, MATLAB, Shell Scripting
* **Deep Learning Frameworks**: PyTorch, TensorFlow, Keras, Hugging Face Transformers
* **Computer Vision**: OpenCV, PIL, Scikit-image, Image Processing
* **LLM & Agents**: RAG, In-context Learning, Multi-Agent Systems, Prompt Engineering
* **Tools & Platforms**: Git, Docker, Linux (Ubuntu), Jupyter, VS Code, FastAPI, ComfyUI
* **Languages**: Chinese (Native), English (Professional – CET-4/6)

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

Projects
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Internships
======
* **Algorithm Intern**, Yizhi Intelligence, Hangzhou
  * March 2025 – June 2025
  * Developed RAG framework using BGE-M3 for low-resource long-sequence generation
  * Built Text-to-Text index library with Re-ranking mechanism
  * Implemented Few-shot In-context Learning for domain-specific QA

* **Algorithm Intern**, Zhixingyuan, Hangzhou
  * November 2025 – December 2025
  * Built script generation Agent with LLM and JSON Schema constraints
  * Developed ComfyUI workflow for automated storyboard generation
  * Integrated LoRA, ControlNet, and IP-Adapter for consistent character generation

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Reviewer for academic conferences and journals
