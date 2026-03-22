---
title: "Hierarchical Retrieval-Augmented Sign Language Semantic Distillation Framework"
collection: portfolio
permalink: /portfolio/rag-sign-distillation
date: 2025-01-02
venue: "Research Project"
authors: '<strong>Daniel Jimmy</strong>'
---

Developed a hierarchical knowledge distillation framework using RAG paradigm with Qwen2.5-7B as the teacher model. Introduced retrieval-augmented generation technology to build In-context Learning context, addressing LLM hallucination issues on low-resource data.

**Key Innovations:**
- Implicit semantic feature Vocab Hit Rate of 94.68%
- Global-Local dual-branch distillation strategy:
  - Global branch: sentence-level semantic alignment
  - Local branch: frame-level fine-grained soft alignment via Sequence Alignment Loss
- Achieved baseline performance in 40 epochs (vs 80 epochs), 2x training efficiency improvement

**Results:**
- Significant reduction in training time while maintaining performance
- Effective solution to hallucination in low-resource scenarios
