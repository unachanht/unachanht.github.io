---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div style="margin-bottom: 1.5em;">
  <h1 style="margin-bottom: 0.2em;">Hi, I'm Una 👋</h1>
  <p style="font-size: 1.15em; color: #555; margin-top: 0;">
    PhD student in Computer Science and Engineering at the University of Michigan, advised by
    <a href="https://web.eecs.umich.edu/~zmao/">Prof. Z. Morley Mao</a> in the
    <a href="https://robustnet-group.github.io/">RobustNet Lab</a>.
  </p>
</div>

---

## Research

My research sits at the intersection of **network systems** and **machine learning systems**. I'm interested in how ML can make networks more adaptive and efficient, and how careful systems design can make ML more reliable and deployable — especially in resource-constrained environments.

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1em; margin: 1.5em 0;">
  <div style="border: 1px solid #e5e5e5; border-radius: 8px; padding: 1em;">
    <h3 style="margin-top: 0;">⚙️ ML Systems Efficiency</h3>
    <p style="margin-bottom: 0;">Making large multimodal models cheaper and faster to serve.</p>
  </div>
  <div style="border: 1px solid #e5e5e5; border-radius: 8px; padding: 1em;">
    <h3 style="margin-top: 0;">🏥 Medical AI</h3>
    <p style="margin-bottom: 0;">ML systems for clinical screening in rural settings.</p>
  </div>
</div>

Before Michigan, I earned my B.S. in Computer Science and Data Science at the **University of Wisconsin–Madison**, where I worked with [Prof. Paul Barford](https://pages.cs.wisc.edu/~pb/) in the DNS Research Group on reinforcement learning for structured domain-name generation.

---

## Publications

**[A Cloud–Edge System for Multimodal Clinical Screening in Resource-Constrained Rural Settings](https://arxiv.org/abs/2608.12745)** \\
<u>Hei Ting Chan</u>, Chenwei Wu, Xueshen Liu, Zesen Zhao, Boyuan Zheng, Luis Filipe Nakayama, Michael G. Morley, Liyue Shen, Jiasi Chen, & Z. Morley Mao \\
*Accepted to Machine Learning for Healthcare (MLHC) 2026.* 🎉

My first-author paper was accepted to **MLHC 2026**. It asks a practical question: how do you deliver specialist-level medical AI where bandwidth is scarce and compute is limited? We pair lightweight, domain-specific models on the edge — which turn raw medical data into compact structured outputs — with a cloud LLM that synthesizes them into clinical summaries, and an LLM orchestrator that picks diagnostic tools based on patient context. Across 20 multimodal cases (cardiac, obstetric, trauma, screening) and network profiles from 500 kbps to 5 Mbps, the hybrid system reaches 98–99% diagnostic tool recall at 92–96% precision, matches or beats cloud-only baselines on clinical accuracy, and holds latency flat at 25–35 s with 4–15x lower token cost.

**[Speculative Decoding for Multimodal Models: A Survey](https://www.preprints.org/manuscript/202603.2344)** \\
Y. Zhang, Y. Wang, Y. Hsieh, et al., including <u>Hei Ting Chan</u> \\
*Preprint; target venue: TMLR. Under review.*

[See all publications →](/publications/)

---

## Elsewhere

- 📝 [Blog posts](/year-archive/)
- 📋 [CV](/cv/)
