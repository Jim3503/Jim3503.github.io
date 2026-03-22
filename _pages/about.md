---
permalink: /
title: "Ming Ji"
author_profile: true
redirect_from:
  - /about/
  - /Danieljimmy.html
---

<a id="about"></a>

## 👋 关于我

我是[浙江大学信息与电子工程学院](https://www.isee.zju.edu.cn/)的硕士研究生，主要研究方向包括**计算机视觉**、**多模态学习**、**大语言模型**以及**基于智能体的系统**。

### 🎓 教育背景

| 时间 | 学校 | 专业 | 学位 |
|------|------|------|------|
| 2024 - 至今 | 浙江大学 | 信息与电子工程 | 硕士 |
| 2020 - 2024 | 吉林大学 | 电子信息工程 | 本科 |

### 🏆 荣誉奖项

- 🥇 浙江大学优秀学生
- 🥇 浙江大学优秀学生干部
- 🥈 吉林大学优秀学生
- 🥈 吉林大学二等奖学金
- 🏅 全国大学生数学竞赛省级一等奖
- 🏅 全国大学生电子设计竞赛省级二等奖
- 📄 发表论文一篇（第一作者）
- 🔬 授权专利一项

💬 欢迎通过邮件与我交流合作：ming.ji@zju.edu.cn

---

<a id="publications"></a>

## 📝 论文发表

{% for post in site.publications reversed %}
**{{ post.title }}**

{{ post.authors }}

{{ post.venue }}, {{ post.date | date: "%Y" }}

[PDF]({{ post.paperurl }}) {% if post.paperurl contains 'github' %}| [代码]({{ post.paperurl }}){% endif %}

{% endfor %}

---

### 🚀 项目经历

{% for post in site.portfolio reversed %}
**{{ post.title }}**

{{ post.venue }} • {{ post.date | date: "%Y" }}

{{ post.excerpt }}

{% endfor %}

---

<a id="internships"></a>

## 💼 实习经历

### 算法实习生
**一知智能**，杭州 (2025.03 – 2025.06)

- 基于 BGE-M3 开发 RAG 框架，应用于低资源长序列生成任务
- 构建文本到文本索引库，实现 Re-ranking 机制
- 实现少样本 In-context Learning，提升特定领域问答准确性

---

### 算法实习生
**知行元**，杭州 (2025.11 – 2025.12)

- 搭建剧本生成智能体，基于 LLM 实现多轮对话式剧本创作
- 开发 ComfyUI 无代码工作流，实现剧本到分镜图的自动化生成
- 集成 LoRA 风格迁移、ControlNet 姿态控制和 IP-Adapter 角色一致性节点

---

## 📧 联系方式

[📧 邮箱](mailto:ming.ji@zju.edu.cn) | [🐙 GitHub](https://github.com/Jim3503)
