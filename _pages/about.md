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

Shuo Cai (蔡硕) is a Master of Philosophy student in the Department of Computing at The Hong Kong Polytechnic University (PolyU), supervised by Prof. Hongxia Yang. His research interests focus on efficient post-training of Large Language Models (LLMs). He is currently working on enhancing LLM reasoning capabilities in coding and mathematical tasks, with a focus on alignment, low resources, and scalable adaptation.


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/InfiAlign.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

InfiAlign: A Scalable and Sample-Efficient Framework for Aligning LLMs to Enhance Reasoning Capabilities

**Shuo Cai**, Sihao Lu, Qihang Zhou, Kejing Yang, Zhijie Sang, Congkai Xie, Hongxia Yang

[**PDF**](https://arxiv.org/pdf/2508.05496) 

- This paper introduces InfiAlign, a scalable and sample-efficient post-training framework that enhances the reasoning capabilities of large language models while sharply reducing data and computational costs. Combining supervised fine-tuning (SFT) with Direct Preference Optimization (DPO), InfiAlign employs an automated data selection pipeline that curates high-quality alignment data from diverse open-source reasoning corpora using multi-dimensional metrics for diversity, difficulty, and quality. Applied to the Qwen2.5-Math-7B-Base model, it achieves performance on par with or surpassing leading distilled baselines such as R1-Distill-Qwen-7B, while using only 12% of their training data—showcasing that principled alignment strategies can deliver state-of-the-art results without prohibitive resource demands.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/Infir.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Infir: Crafting effective small language models and multimodal small language models in reasoning

Congkai Xie, **Shuo Cai**, Wenqi Wang, Peiyi Li, Zhijie Sang, Kejing Yang, Yining Di, Zeyu Liu, Guohao Zhu, Zihan Liu, Hongxia Yang

[**PDF**](https://arxiv.org/pdf/2502.11573) 

- This paper explores the development of efficient Small Language Models (SLMs) and Multimodal Small Language Models (MSLMs) that maintain strong reasoning abilities. It introduces an innovative training pipeline designed to enhance reasoning skills while enabling easy deployment on edge devices. The proposed approach achieves SoTA performance while keeping development costs low. InfR aims to improve AI systems by strengthening reasoning capabilities, lowering adoption barriers, and addressing privacy concerns through compact model sizes.

</div>
</div>



# 📖 Educations
- *2025.09 - present*, MPhil, Department of Computing, The Hong Kong Polytechnic University.
- *2021.09 - 2025.06*, Undergraduate, Intelligent Science and Technology, School of Automation Science and Engineering, South China University of Technology.

# 💻 Internships
- *2025.06 - 2025.09*, Research Intern, [Infix.ai](https://infix-ai.com/), Shenzhen.
