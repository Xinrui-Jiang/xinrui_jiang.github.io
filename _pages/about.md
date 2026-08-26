---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi there, I'm Xinrui (Ryan) Jiang, a master's student in EE at Stanford University. Prior to that, I received my B.Eng from Fudan University. During my undergraduate study, I was fortunate to be advised by Professor <a href='https://taco-group.github.io/index.html'>Zhengzhong Tu</a> at Texas A&M University and Professor <a href='https://nmr.mgh.harvard.edu/~berkin/index.html'>Berkin Bilgic</a> at Martinos Center for Biomedical Imaging/Harvard Medical School. 

My current interests include AI agents and visual creation, with recent work on tool-using agents for video editing and generative model evaluation. My earlier research focused on low-level vision, including image super-resolution and quantitative MRI reconstruction. I enjoy starting from real-world needs and observations, framing concrete technical problems, and developing practical methods and systems to address them.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/4kagent.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**4KAgent: Agentic Any Image to 4K Super-Resolution**

Yushen Zuo, Qi Zheng, Mingyang Wu, **Xinrui Jiang**, Renjie Li, Jian Wang, Yide Zhang, Gengchen Mai, Lihong V. Wang, James Zou, Xiaoyu Wang, Ming-Hsuan Yang, Zhengzhong Tu

[**Paper**](https://arxiv.org/abs/2507.07105) · [**Code**](https://github.com/taco-group/4KAgent) · [**Project Page**](https://4kagent.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We present 4KAgent, an agentic image super-resolution generalist designed to universally upscale any image to 4K resolution, regardless of input type, degradation level, or domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='images/nlcgnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**NLCG-Net: A Model-Based Zero-Shot Learning Framework for Undersampled Quantitative MRI Reconstruction**

**Xinrui Jiang**, Yohan Jun, Jaejin Cho, Mengze Gao, Xingwang Yong, Berkin Bilgic

[**Paper**](https://arxiv.org/abs/2401.12004) · [**Code**](https://github.com/Xinrui-Jiang/NLCG-Net) · [**Presentation**](https://www.youtube.com/watch?v=nFp378a-ygU) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We purposed NLCG-Net, a model-based and data-driven framework achieved via self-supervised learning, which incorporates nonlinear conjugate gradient optimization and Neural Network Regularization in a iterative manner and achieves zero-shot quantitative MRI reconstruction.
</div>
</div>

# 📌 Projects
<div class='paper-box'><div class='paper-box-image'><div><img src='images/sumforu.png' alt="SumForU" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SUMFORU: An LLM-Based Review Summarization Framework for Personalized Purchase Decision Support**

[**Report**](https://arxiv.org/abs/2512.11755) · [**Code**](https://github.com/Harry20030331/SumForU)

- We developed SumForU, a persona-steerable review summarization system built on Thinking Machine's Tinker platform. This system fine-tunes LLMs on Amazon 2023 reviews and optimizes for user-aligned summaries via preference-based reinforcement learning.
</div>
</div>


# 💻 Internships
- *2026.06 - 2026.09*, Machine Learning Engineer at [DoorDash](https://merchants.doordash.com/en-us).
  <span class="internship-summary">Agentic editing orchestrator for multi-defect video repair</span>
- *2025.03 - 2025.08*, Machine Learning Engineer at [Microsoft](https://www.microsoft.com/en-us/aprd/aboutus/team-stca).
  <span class="internship-summary">Failure-driven, self-refining LLM-as-a-Judge for large-scale generative media evaluation</span>
- *2024.01 - 2024.04*, Machine Learning Engineer at [TikTok/Bytedance](https://www.bytedance.com/en-us/).
  <span class="internship-summary">Multimodal content understanding and unsupervised mining for short-form video</span>

# 🎖 Selected Awards
- *2023.09* Suiwei Scholarship (top 1%)
- *2022.09* National Scholarship (top 1%)

# 🌟 Fun
In my spare time, I enjoy running (about 3.2 miles each time), building LEGO sets, and hanging out with my American Shorthair cat, Dafu.

<div class="fun-gallery">

  <img src="{{ site.baseurl }}/images/fun_1.jpg" alt="My LEGO collection">

  <img src="{{ site.baseurl }}/images/my_dafu.jpg" alt="My cat Dafu">

</div>
