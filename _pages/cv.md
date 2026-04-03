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
* **M.S.** in Electronic Information (Information & Electronic Engineering), Zhejiang University, 2024–present
  * College of Information Science and Electronic Engineering
  * **Research Focus**: Computer Vision, Multimodal Understanding, Agent Algorithms
  * **Awards**: Outstanding Student, Zhejiang University (2024); Outstanding Student Leader, Zhejiang University (2024)
  * **Publications**: 1 CCF-C conference paper (1st author, PAKDD 2026 Oral); 1 CCF-A journal paper under review (Journal of Computer Research and Development)
  * **Patents**: 1 authorized patent

* **B.S.** in Electronic Information Engineering, Jilin University, 2020–2024
  * School of Electronic Science and Engineering
  * **Awards**:
    - National Outstanding Completion, College Student Innovation and Entrepreneurship Training Program (2024)
    - Provincial First Prize, National Undergraduate Mathematics Competition (2023)
    - Provincial Second Prize, National Undergraduate Electronic Design Competition (2022)
    - Outstanding Bachelor's Thesis, Jilin University (2024)

Research Interests
======
* **Computer Vision**: Image recognition, object detection, visual understanding, Sign Language Translation
* **Multimodal Learning**: Vision-language models, cross-modal learning, multimodal understanding
* **Large Language Models**: Training and fine-tuning large-scale models, Retrieval-Augmented Generation (RAG)
* **Agent Systems**: Multi-Agent systems, task decomposition, workflow orchestration, memory mechanisms

Skills
======
* **Programming Languages**: Python (proficient), C++, MATLAB, Shell Scripting
* **Deep Learning Frameworks**: PyTorch (primary), TensorFlow, Keras, Hugging Face Transformers
* **Computer Vision**: OpenCV, PIL, Scikit-image, Image Processing, ComfyUI workflows
* **LLM & Agents**: RAG, In-context Learning, Multi-Agent Systems (CrewAI), Prompt Engineering, JSON Schema constraints
* **Web & Tools**: FastAPI, Git, Docker, Linux (Ubuntu), Jupyter, VS Code
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
* **Tradeclaw - Multi-Agent Intelligent Investment Research System** (Personal Project)
  * Designed and orchestrated multi-agent collaborative chain including Data Collection Agent, Market Narrative Agent, Technical Analysis Agent, and Report Generation Agent
  * Implemented full pipeline from real-time market API integration, historical K-line backtesting to investment advice generation
  * **Innovation**: Designed RAG-enhanced hierarchical memory system (Policy/Episodic/Reflection three-layer architecture) with BM25 + Embedding hybrid retrieval

* **FashionClaw - E-commerce Virtual Try-on Generation Skill** (Personal Project)
  * Built "character preservation + garment replacement" multi-image conditional generation pipeline
  * Completed full-chain engineering encapsulation: image preprocessing, model scheduling, result parsing, log management
  * Supported multi-model switching and third-party multimodal model integration

Internships
======
* **RAG Algorithm Intern**, Yizhi Intelligence, Hangzhou (Feb 2025 – Jun 2025)
  * **Background**: Addressed semantic fragmentation in automotive outbound call knowledge base scenarios
  * **Solution**: Reconstructed RAG system based on Contextual Retrieval paradigm with BGE-M3 + BM25 hybrid indexing and Cross Encoder reranking
  * **Results**: Core knowledge Top-3 recall +12pt; numerical fact accuracy +15pt; internal quality pass rate +17pt

* **LLM Algorithm Intern**, Zhixingyuan, Hangzhou (Nov 2025 – Jan 2026)
  * **Multi-turn Dialogue Script Agent**: Built CrewAI-based Agent architecture with JSON Schema constraints and FastAPI service interfaces
  * **Storyboard Generation**: Integrated ComfyUI workflows for automated script-to-storyboard generation
  * **Video Editing Dataset**: Constructed low-cost Image-to-Video dataset generation pipeline using Wan2.2-TI2V-5B and DiffSynth-Studio

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Reviewer for academic conferences and journals
