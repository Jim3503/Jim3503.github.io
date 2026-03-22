---
permalink: /
title: "Ming Ji"
author_profile: true
redirect_from:
  - /about/
  - /Danieljimmy.html
---

<a id="about"></a>

## About Me
<!-- 
I'm a master's student at the [College of Information Science and Electronic Engineering](https://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). My research interests include computer vision, multimodal learning, large language models, and training deep neural networks on large-scale datasets. -->
I’m a master’s student at the [College of Information Science and Electronic Engineering](https://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). My research interests include computer vision, multimodal learning, large language models, and agent-based intelligent systems.


### Education

**M.S.** in Information Science and Electronic Engineering, Zhejiang University (2024–present)

**B.S.** in Electronic Information Engineering, Jilin University (2020–2024)

<!-- ### Skills

**Programming**: Python, C++, MATLAB, Shell Scripting

**Deep Learning**: PyTorch, TensorFlow, Keras, Hugging Face Transformers

**Computer Vision**: OpenCV, PIL, Scikit-image, Image Processing

**LLM & Agents**: RAG, In-context Learning, Multi-Agent Systems, Prompt Engineering

**Tools**: Git, Docker, Linux (Ubuntu), Jupyter, VS Code, FastAPI, ComfyUI -->


### Awards & Honors

- One paper published as first author; one authorized patent granted
- Outstanding Student, Zhejiang University
- Outstanding Student Leader, Zhejiang University
- Outstanding Student, Jilin University
- Second-Class Scholarship, Jilin University
- First Prize, National Undergraduate Mathematics Competition (Provincial Level)
- Second Prize, National Undergraduate Electronic Design Competition (Provincial Level)

💬 Feel free to drop me emails (ming.ji@zju.edu.cn) if you have interests in above topics, and collaborations are welcomed.

---

<a id="publications"></a>

## Publications

{% for post in site.publications reversed %}
**{{ post.title }}** <br>
{{ post.authors }} <br>
{{ post.venue }}, {{ post.date | date: "%Y" }} <br>
[PDF]({{ post.paperurl }}) {% if post.paperurl contains 'github' %}| [Code]({{ post.paperurl }}){% endif %}

{% endfor %}

### Projects

{% for post in site.portfolio reversed %}
**{{ post.title }}**

{{ post.venue }} • {{ post.date | date: "%Y" }}

{{ post.excerpt }}

{% endfor %}

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

## Contact

[Email](mailto:ming.ji@zju.edu.cn) / [Github](https://github.com/Jim3503) 
