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

I am an undergraduate student at ShanghaiTech University, majoring in Computer Science and Technology. My current research interests are **multimodal learning** and **large-scale models** (foundation models, large language models). I focus on computer vision, vision-language understanding, optimization for deep networks, and model robustness.

- **Email:** weizhx2022@shanghaitech.edu.cn
- **GitHub:** [nagara214](https://github.com/nagara214)
- **Location:** Shanghai, China

<!-- Google Scholar badge -->
<!--
You can enable your scholar badge here if you have a scholar profile.
<a href='YOUR_GOOGLE_SCHOLAR_URL'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>
-->

# 🔥 News

- *2025.06*: Our work on augmenting moment retrieval and weakly-supervised affordance grounding was accepted by ICCV 2025!
- *2025.02*: Started as a Teaching Assistant for Artificial Intelligence at ShanghaiTech University.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Augmenting Moment Retrieval: Zero-Dependency Two-Stage Learning**  
Zhengxuan Wei\*, Jiajin Tang\*, Sibei Yang†  
[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)  
*International Conference on Computer Vision (ICCV), 2025*  
A novel residual learning framework for moment retrieval, introducing Splice-and-Boost augmentation and dual-path distillation to enable superior boundary localization and semantic discrimination without external data.

</div>
</div>

- **Closed-Loop Transfer for Weakly-supervised Affordance Grounding**, Jiajin Tang\*, Zhengxuan Wei\*, Ge Zheng, Sibei Yang†, *ICCV 2025.*
- **Sim-DETR: Unlock DETR for Temporal Sentence Grounding**, Jiajin Tang\*, Zhengxuan Wei\*, Yuchen Zhu, Cheng Shi, Guanbin Li, Liang Lin, Sibei Yang†, *ICCV 2025.*
- **Rethinking Query-based Transformer for Continual Image Segmentation**, Yuchen Zhu\*, Cheng Shi\*, Dingyou Wang, Jiajin Tang, Zhengxuan Wei, Yu Wu, Guanbin Li, Sibei Yang†, *CVPR 2025.*

# 🎖 Honors and Awards

- *2024.12* ShanghaiTech Outstanding Student

# 💻 Research Projects

- **Preserving Intra-Modal Consistency in Externally Guided Image Clustering**  
  Developed a framework integrating external semantic guidance with internal feature consistency, enhancing clustering performance.
- **Evaluation and Fine-Tuning of LLMs for Optimization Problem Transformation**  
  Evaluated and fine-tuned large language models for transforming natural-language linear programming problems into mathematical formulations.
- **Deep Learning for 3D Kidney Vessel Segmentation**  
  Proposed a 2.5D Swin Transformer approach with multi-axis inference and edge pixel dropping to improve 3D segmentation.

# 📖 Education

- *2022.09 – Present*, **B.Eng. in Computer Science and Technology**, ShanghaiTech University, China

# 💬 Contact

- Email: weizhx2022@shanghaitech.edu.cn
- GitHub: [nagara214](https://github.com/nagara214)
- Location: Shanghai, China
