---
title: "用博客记学习笔记"
lang: zh
lang_switch: /
date: 2026-09-18
categories:
  - 学习笔记
tags:
  - 说明
---

中英导航都指向同一份博客。文章用 **Markdown** 写（需要时也可以直接写 HTML），放在 `_posts/YYYY-MM-DD-标题.md`。

主题已支持：公式（MathJax）、流程图（Mermaid）、交互图（Plotly）。写法示例见正文下面。

## 公式

公式用 `$$...$$`：

$$
\mathcal{L} = -\sum_{i} y_i \log \hat{y}_i
$$

## 流程图

```mermaid
flowchart LR
  A[读论文] --> B[写笔记]
  B --> C[实验]
  C --> B
```

## 交互图

鼠标可悬停查看数值：

```plotly
{
  "data": [
    {
      "x": [1, 2, 3, 4],
      "y": [0.62, 0.71, 0.74, 0.81],
      "type": "scatter",
      "mode": "lines+markers",
      "name": "NDCG@10"
    }
  ],
  "layout": {
    "xaxis": {"title": "epoch"},
    "yaxis": {"title": "score"}
  }
}
```
