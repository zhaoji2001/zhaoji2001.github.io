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

Welcome to my homepage.I am a student in the second year of my master's degree, currently studying in Beijing University of Technology, College of Information Science and Technology.My major is electronic information. The directions I am more interested in are Machine Learning, Deep Neural Networks, Pattern Recognition, Image Processing, Continul Learning, Few-shot Learning and Few-Shot Incremental Learners.
My first work on continuous learning is in preparation.




# 🔥 News

- *2024.10: &nbsp;🎉🎉 The latest research has yielded excellent results and is being prepared for publication.

# 📝 Publications 

Adapter Enhanced Semantic Prompting for Continual learning

Huajie Jiang, Ji Zhao, Yongli Hu, Baocai Yin, Jiaseng Zhang

<img src="images/motivation.png" style="zoom:50%;" />

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong></strong>

- Continual learning enables models to adapt to evolving data streams without retraining from scratch. However, it faces the issue of catastrophic forgetting, where new learning overwrites previously acquired knowledge. Recent advancements in natural language processing have shown that using language prompts can guide model learning and help retain knowledge. Nevertheless, since language and images reside in distinct embedding spaces, effectively leveraging language to guide visual models remains a critical challenge. In this paper, we propose a novel language-guided continual learning framework that combines prompt tuning and adapter techniques within a Vision Transformer (ViT) architecture. Our method processes interactions between language prompts and images using self-attention modules, followed by refinement through adapters. To enhance the model's responsiveness to language guidance, we introduce a new cosine contrastive loss function and initialize language prompts with fixed features to ensure consistency in language embeddings. Furthermore, we develop an Integrated Query-Key Matching Mechanism that employs multiple strategies to enhance task matching accuracy. Extensive experiments on three continual learning datasets demonstrate that our approach achieves state-of-the-art (SOTA) performance across multiple metrics, highlighting its potential for advancing continual learning.

- Others



# 📖 Educations

- *2023.09 - 2024.10 (now)*, Beijing University of Technology, College of Information Science and Technology. Electronic Information. 
- *2019.09 - 2023.06*, LiaoNing Petrochemical University, School of Information and Control Engineering, Control Engineering. 

# 💻 Internships

- Pipeline
