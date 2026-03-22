---
permalink: /
title: "Daniel Jimmy"
author_profile: true
redirect_from:
  - /about/
  - /Danieljimmy.html
---

<a id="about"></a>

## About Me

I'm a master's student at the [College of Information Science and Electronic Engineering](https://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). My research interests include computer vision, multimodal learning, large language models, and training deep neural networks on large-scale datasets.

### Research Focus

I am particularly interested in:
- **Computer Vision**: Image recognition, object detection, and visual understanding
- **Multimodal Learning**: Vision-language models and cross-modal learning
- **Large Models**: Training and fine-tuning large-scale deep learning models
- **Deep Learning**: Developing efficient training methods for large datasets

### Background

I completed my undergraduate studies at [Jilin University](https://www.jlu.edu.cn/) with a B.S. in Electronic Information Engineering, where I worked at the [State Key Laboratory on Integrated Optoelectronics](http://sklio.jlu.edu.cn/).

💬 Feel free to drop me emails (ming.ji@zju.edu.cn) if you have interests in above topics, and collaborations are welcomed.

---

<a id="education"></a>

## Education

### M.S. in Information Science and Electronic Engineering
**Zhejiang University** (2024–present)
- College of Information Science and Electronic Engineering
- **Achievements**: Published 1 paper (1st author, international conference); 1 CCF-A journal paper under review; 1 authorized patent

### B.S. in Electronic Information Engineering
**Jilin University** (2020–2024)
- State Key Laboratory on Integrated Optoelectronics
- **Awards**:
  - First Prize, National Undergraduate Mathematics Competition (Provincial Level)
  - Second Prize, National Undergraduate Electronic Design Competition (Provincial Level)
  - Second-Class Scholarship, Jilin University
  - Outstanding Student, College Level

---

<a id="publications"></a>

## Publications

{% for post in site.publications reversed %}
### {{ post.title }}
{{ post.venue }} • {{ post.date | date: "%Y" }}

{{ post.excerpt }}

[View Details]({{ post.url }}) {% if post.paperurl %}[PDF]({{ post.paperurl }}){% endif %} {% if post.paperurl contains 'github' %}[Code]({{ post.paperurl }}){% endif %}

{% endfor %}

---

<a id="projects"></a>

## Projects

{% for post in site.portfolio reversed %}
### {{ post.title }}
{{ post.venue }} • {{ post.date | date: "%Y" }}

{{ post.excerpt }}

[View Details]({{ post.url }})

{% endfor %}

---

<a id="skills"></a>

## Skills

**Programming Languages**: Python, C++, MATLAB, Shell Scripting

**Deep Learning Frameworks**: PyTorch, TensorFlow, Keras, Hugging Face Transformers

**Computer Vision**: OpenCV, PIL, Scikit-image, Image Processing

**LLM & Agents**: RAG, In-context Learning, Multi-Agent Systems, Prompt Engineering

**Tools & Platforms**: Git, Docker, Linux (Ubuntu), Jupyter, VS Code, FastAPI, ComfyUI

**Languages**: Chinese (Native), English (Professional – CET-4/6)

---

<a id="internships"></a>

## Internships

### Algorithm Intern
**Yizhi Intelligence, Hangzhou** (March 2025 – June 2025)

- Developed RAG framework using BGE-M3 for low-resource long-sequence generation
- Built Text-to-Text index library with Re-ranking mechanism
- Implemented Few-shot In-context Learning for domain-specific QA

### Algorithm Intern
**Zhixingyuan, Hangzhou** (November 2025 – December 2025)

- Built script generation Agent with LLM and JSON Schema constraints
- Developed ComfyUI workflow for automated storyboard generation
- Integrated LoRA, ControlNet, and IP-Adapter for consistent character generation

---

<a id="contact"></a>

## Contact

[Email](mailto:ming.ji@zju.edu.cn) / [Github](https://github.com/Jim3503) 
