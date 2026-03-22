---
permalink: /
title: "Daniel Jimmy"
author_profile: true
redirect_from:
  - /about/
  - /Danieljimmy.html
---

I'm a master's student at the [College of Information Science and Electronic Engineering](https://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). My research interests include computer vision, multimodal learning, large language models, and training deep neural networks on large-scale datasets.

💬 Feel free to drop me emails (ming.ji@zju.edu.cn) if you have interests in above topics, and collaborations are welcomed.

<a id="news"></a>

## 🔥 News

| Date | News |
|------|------|
| 2025 | 🎉 Started master's studies at Zhejiang University |
| 2025 | 📝 Paper submitted to Chinese Journal of Computers (CCF-A, under review) |
| 2025 | 🏆 One authorized patent granted |
| 2025 | 📢 Paper accepted by PAKDD 2026 (CCF-C Conference) |
| Nov 2025 | 💼 Algorithm Intern at Zhixingyuan |
| Mar 2025 | 💼 Algorithm Intern at Yizhi Intelligence |
| 2024 | 🎓 Completed B.S. at Jilin University with honors |

<a id="publications"></a>

## 📝 Selected Publications

Full publication list can be found on Google Scholar.

{% for post in site.publications reversed %}
### {{ post.title }}

{{ post.authors }}

{{ post.venue }}, {{ post.date | date: "%Y" }}

[[PDF]]({{ post.paperurl }}) {% if post.paperurl contains 'github' %}[[Code]]({{ post.paperurl }}){% endif %} [[BibTeX](#)]

{{ post.excerpt }}

{% endfor %}

<a id="education"></a>

## 🎓 Education

**M.S.** in Information Science and Electronic Engineering, Zhejiang University (2024–present)

**B.S.** in Electronic Information Engineering, Jilin University (2020–2024)

<a id="projects"></a>

## 🚀 Projects

{% for post in site.portfolio reversed %}
### {{ post.title }}

{{ post.venue }}

{{ post.excerpt }}

{% endfor %}

<a id="internships"></a>

## 💼 Internships

**Algorithm Intern**, Yizhi Intelligence, Hangzhou (March 2025 – June 2025)

Developed RAG framework using BGE-M3 for low-resource long-sequence generation. Built Text-to-Text index library with Re-ranking mechanism.

**Algorithm Intern**, Zhixingyuan, Hangzhou (November 2025 – December 2025)

Built script generation Agent with LLM and JSON Schema constraints. Developed ComfyUI workflow for automated storyboard generation.

<a id="awards"></a>

## 🏆 Awards & Honors

- First Prize, National Undergraduate Mathematics Competition (Provincial Level)
- Second Prize, National Undergraduate Electronic Design Competition (Provincial Level)
- Second-Class Scholarship, Jilin University
- Outstanding Student, College Level
- Published 1 paper (1st author)
- 1 authorized patent

<a id="skills"></a>

## 🔧 Skills

**Programming**: Python, C++, MATLAB, Shell Scripting

**Deep Learning**: PyTorch, TensorFlow, Keras, Hugging Face Transformers

**Computer Vision**: OpenCV, PIL, Scikit-image, Image Processing

**LLM & Agents**: RAG, In-context Learning, Multi-Agent Systems, Prompt Engineering

**Tools**: Git, Docker, Linux (Ubuntu), Jupyter, VS Code, FastAPI, ComfyUI

**Languages**: Chinese (Native), English (CET-4/6)

<a id="contact"></a>

## 📧 Contact

[Email](mailto:ming.ji@zju.edu.cn) / [Github](https://github.com/Jim3503) 
