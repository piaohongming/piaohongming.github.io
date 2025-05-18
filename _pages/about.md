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

I am a second year PhD student at City University of Hong Kong under the supervision of Prof. Ying Wei and Prof. Dapeng Oliver Wu. I received my Bachelor degree in Beihang University (2019-2023). I am now working on continual learning. I have published three papers at the top international conferences (e.g., ICML, KDD) with total <a href='https://scholar.google.com/citations?user=_shIrtAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Our paper [SD-LoRA: Scalable Decoupled Low-Rank Adaptation for Class Incremental Learning](https://openreview.net/forum?id=5U1rlpX68A) is accepted by ICLR 2025 oral.
- *2024.09*: &nbsp;🎉🎉 Happy to receive Research Tuition Scholarship!
- *2024.06*: &nbsp;🎉🎉 Happy to receive the ICML Travel Award (2024)!
- *2024.05*: &nbsp;🎉🎉 Our paper [Warming Up Cold-Start CTR Prediction by Learning Item-Specific Feature Interactions](https://arxiv.org/pdf/2407.10112) is accepted by KDD 2024. 
- *2024.05*: &nbsp;🎉🎉 Our paper [Federated Continual Learning via Prompt-based Dual Knowledge Transfer](https://openreview.net/pdf?id=Kqa5JakTjB) is accepted by ICML 2024.

# 📝 Publications 

- [SD-LoRA: Scalable Decoupled Low-Rank Adaptation for Class Incremental Learning](https://openreview.net/forum?id=5U1rlpX68A), Yichen Wu^, **Hongming Piao^**, Long-Kai Huang, Renzhen Wang, Wanhua Li, Hanspeter Pfister, Deyu Meng, Kede Ma, Ying Wei, **ICLR 2025 oral**
- [Warming Up Cold-Start CTR Prediction by Learning Item-Specific Feature Interactions](https://arxiv.org/pdf/2407.10112), Yaqing Wang, **Hongming Piao**, Daxiang Dong, Quanming Yao, Jingbo Zhou, **KDD 2024**
- [Federated Continual Learning via Prompt-based Dual Knowledge Transfer](https://openreview.net/pdf?id=Kqa5JakTjB), **Hongming Piao^**, Yichen Wu^, Dapeng Wu, Ying Wei, **ICML 2024**
- [MtCut: A Multi-Task Framework for Ranked List Truncation](https://dl.acm.org/doi/abs/10.1145/3488560.3498466), Dong Wang, Jianxin Li, Tianchen Zhu, Haoyi Zhou, Qishan Zhu, Yuxin Wen, **Hongming Piao**, **WSDM 2022**

# 🎖 Honors and Awards
- *2024.06* ICML Travel Award. 
- *2024.09* Research Tuition Scholarship. 

# 📖 Educations
- *2023.09 - Now*, PhD, Computer Science, City University of Hong Kong. 
- *2019.09 - 2023.06*, Undergraduate, Computer Science, Beihang University. 

# 💻 Internships
- *2022.08 - 2023.05*, Baidu Research, supervised by Dr. Yaqing Wang.
