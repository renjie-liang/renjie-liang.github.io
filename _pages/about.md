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

# 💡 About Me
<span class='anchor' id='about-me'></span>

Hi! I'm currently a master student from **National University of Singapore (NUS)**. Meanwhile, I'm a research intern of the [NExT Research Center](https://www.nextcenter.org/) in the school of computing working with Prof. Tat-Seng Chua. Before that, I obtained my Bachelor in Software Engineering from the **TongJi University**, Shanghai, China in 2022. My research interests focuses on software engineering (neural code search) and artificial intelligence (multimodal understanding).

# 🔥 Work Experiences
Research Intern, School of Software Engineering, TongJi University.            
<div style="text-align: right;">
08/2020-06/2022
</div>

<div style="text-align: right;">
Prof. Yan Liu
</div>

Mainly focus on neural code search and neural code completion.

Research Intern, NUS Centre for Extreme Search (NExT++), NUS.            
<div style="text-align: right;">
06/2022-present
</div>

<div style="text-align: right;">
Prof. Tat-Seng Chua
</div>

Mainly focus on multimodal fusion and understanding.


# 📝 Publications 

- **On the Importance of Building High-quality Training Datasets for Neural Code Search**

  Abstract: *Extracted code snippets & comments from open-source sites (e.g., Stack Overflow, GitHub).
  Introduced a 2-step framework: rule-based & model-based filtering. Rule-based step applies heuristics to find abnormal syntax. Model-based step uses Variational Auto-Encoder to detect semantic outliers. Experiments show our framework boosts code search model performance with 50% data reduction.*

  Zhensu Sun, **Li Li**, Yan Liu, Xiaoning Du, and Li Li

  **ICSE 2022, Nominated for distinguished paper**

- **Biased-Predicate Annotation Identification via Unbiased Visual Predicate Representation**

  Abstract: *Introduce a novel perspective and an approach for scene graph generation and panoptic scene graph generation methods debiasing. The proposed method aims to learn unbiased visual representation for accurate biased-annotation identification. Experimental results demonstrate that the proposed method significantly enhances the performance of benchmark models on the PSG\VG dataset,
  achieving a new state-of-the-art performance.*

  **Li Li**, Chenwei Wang, You Qin, Wei Ji, and Renjie Liang

  **ACM MM 2023, Accepted with full marks**

- **Panoptic Scene Graph Generation with Semantics-prototype Learning**

  Abstract: *We propose a novel framework named ADTrans to adaptively transfer biased predicate annotations to informative and unified ones. To promise consistency and accuracy during the transfer process, we propose to observe the invariance degree of representations in each predicate class, and learn unbiased prototypes of predicates with different intensities. Meanwhile, we continuously measure the distribution changes between each presentation and its prototype, and constantly screen potentially biased data. Finally, with the unbiased predicate-prototype representation embedding space, biased annotations are easily identified.Experiments show that ADTrans significantly improves the performance of benchmark models, achieving a new state-of-the-art performance, and shows great generalization and effectiveness on multiple datasets.*

  **Li Li**, Wei Ji, Yiming Wu, Mengze Li, You Qin, Lina Wei, Roger Zimmermann

  **Submitted to AAAI 2024**

- **Domain-wise Invariant Learning for Panoptic Scene Graph Generation**

  Abstract: *To address the intrinsic bias in Panoptic Scene Graph Generation, we propose a novel framework to infer potentially biased annotations by measuring the predicate prediction risks within each subject-object pair (domain), and adaptively transfer the biased annotations to consistent ones by learning invariant predicate representation embeddings. Experiments show that our method significantly improves the performance of benchmark models, achieving a new state-of-the-art performance, and shows great generalization and effectiveness on PSG dataset.*

  **Li Li**, You Qin, Wei Ji, Yuxiao Zhou, Roger Zimmermann

  **Submitted to ICASSP 2024**

- **Transfer Visual Prompt Generator across LLMs**

  Abstract: *Investigate the visual prompt generator transferability across LLMs. Design an effective two-stage transfer framework to speed up the learning process. The design framework achieves over 10 times speed-up and 10.7% training data compared with connecting a visual prompt generator to BLIP-2 OPT from scratch. With our framework, one can build a novel high-performance vision-language LLM at affordably lower cost.*

  Ao Zhang, Hao Fei, Yuan Yao, Wei Ji, **Li Li**, Zhiyuan Liu, Tat-Seng Chua

  **Submitted to NeurIPS 2023**

- **Towards Complex-query Referring Image Segmentation: A Novel Benchmark**

  Abstract: *We highlight the significant of semantic understanding capability of large pre-trained models. Thus, we propose a novel benchmark which contains enriched specific and informative queries, and more realistic scenarios. Meanwhile, we also propose a baseline method using dual-modality graph alignment to better task the benchmark.*

  Wei Ji, **Li Li**, Hao Fei, Xiangyan Liu, Juncheng Li, Roger Zimmermann

  **Submitted to ICLR 2024**

# 📖 Educations

  <div class='school-box'>
  2022.08 - now

  Master of Science in Industry 4.0

  **National University of Singapore**, Singapore

  </div>

  <div class='school-box'>
  2018.08 - 2022.06

  Bachelor of Engineering in Software Engineering

  **TongJi University**, Shanghai

  </div>
