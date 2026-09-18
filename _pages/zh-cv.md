---
layout: archive
title: "简历"
permalink: /zh/cv/
lang: zh
lang_switch: /cv/
author_profile: true
---

{% include base_path %}

一页版介绍。邮箱：[wangkaibo72@gmail.com](mailto:wangkaibo72@gmail.com)。

研究方向
======
信息检索与推荐系统（序列 / 跨域排序、LLM for RecSys）；时空表示学习。也关注基础模型与具身智能中可迁移的序列建模问题。

教育背景
======
* **伦敦国王学院**，人工智能硕士，2025.09 -- 2027.01（预计）
  * 排名前 10%
  * 硕士课题：SPR-Learning，从长演示中学习抽象技能
* **北京理工大学**，数据科学与大数据技术学士，2021.08 -- 2025.06
  * GPA 3.5/4.0；优秀毕业论文
  * 课程：机器学习、深度学习、强化学习、自然语言处理、计算机视觉

科研经历
======
* **研究助理**，北京理工大学，2024.12 -- 至今
  * 合作导师：王树良教授、朱佳宝
  * 作为唯一学生作者完成两项研究：问题定义、模型设计、实验与写作
* **硕士课题**，伦敦国王学院，2026.04 -- 2026.08
  * SPR-Learning：RQ-VAE 技能码本、causal Transformer 高层规划、conditional diffusion 底层动作
  * 在厨房仿真环境的 9 自由度机械臂上，长程任务完成率高于传统规划器及部分 VLA baseline

实习
======
* **算法实习生**，内蒙古金财信息技术有限公司（银行事业部），2024.06 -- 2024.08
  * 基于 PaddleOCR 完成发票等财务票据识别：数据、微调与银行场景部署

论文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

项目
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

技能
======
* **研究：** 信息检索、推荐系统、时空建模、LLM for RecSys、强化学习、迁移学习
* **工具：** Python，PyTorch，C++
* **语言：** 英语（雅思 7.5）；中文（母语）
