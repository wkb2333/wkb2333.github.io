---
layout: archive
title: "CV"
permalink: /cv/
lang: en
lang_switch: /zh/cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A short academic résumé. Email: [wangkaibo72@gmail.com](mailto:wangkaibo72@gmail.com).

Research interests
======
Information retrieval and recommender systems (sequential / cross-domain ranking, LLM for RecSys); spatiotemporal representation learning. Open to adjacent problems in foundation models and embodied intelligence where sequential modeling transfers.

Education
======
* **King's College London**, MSc in Artificial Intelligence, Sep. 2025 -- Jan. 2027 (expected)
  * Ranked top 10%
  * Master's thesis: SPR-Learning — learning abstract skills from long demonstrations
* **Beijing Institute of Technology**, B.Eng. in Data Science and Big Data Technology, Aug. 2021 -- Jun. 2025
  * GPA 3.5/4.0; Outstanding Undergraduate Thesis
  * Coursework: machine learning, deep learning, reinforcement learning, NLP, computer vision

Research experience
======
* **Research Assistant**, Beijing Institute of Technology, Dec. 2024 -- present
  * Advisors: Prof. Shuliang Wang and Jiabao Zhu
  * Led two research projects as the only student author: problem formulation, model design, experiments, and writing
* **Master's project**, King's College London, Apr. 2026 -- Aug. 2026
  * SPR-Learning: RQ-VAE skill codebook, causal Transformer for high-level plans, conditional diffusion for low-level actions
  * On a kitchen simulator with a 9-DoF arm, long-horizon success rates exceeded classical planners and selected VLA baselines

Industry
======
* **Algorithm Intern**, Inner Mongolia Jincai Information Technology (Banking), Jun. 2024 -- Aug. 2024
  * Fine-tuned and deployed PaddleOCR for invoice / financial-document recognition in a banking workflow

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected projects
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Research:** information retrieval, recommender systems, spatiotemporal modeling, LLM for RecSys, reinforcement learning, transfer learning
* **Tools:** Python, PyTorch, C++
* **Languages:** English (IELTS 7.5); Chinese (native)
