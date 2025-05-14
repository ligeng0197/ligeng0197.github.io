+++
author = "Hulingxiao He, Geng Li, Zijun Geng, Jinglin Xu, Yuxin Peng"
title = "Analyzing and Boosting the Power of Fine-Grained Visual Recognition for Multi-modal Large Language Models"
date = "2025-01-25"
conference = "ICLR 2025"
description = "Guide to emoji usage in Hugo"
tags = [
    "MLLMs/LMMs",
    "Fine-grained perception"
]
+++

<img src="/images/finedefics.jpg" alt="Finedefics diagram">
<!-- <img class="avatar" src="images/avatar.jpg" alt="avatar"> -->

**Authors:** Hulingxiao He, <u>Geng Li</u>, Zijun Geng, Jinglin Xu, Yuxin Peng

**Abstract:** Multi-modal large language models (MLLMs) have shown remarkable abilities in various visual understanding tasks. However, MLLMs still struggle with fine-grained visual recognition (FGVR), which aims to identify subordinate-level categories from images. This can negatively impact more advanced capabilities of MLLMs, such as object-centric visual question answering and reasoning. In our study, we revisit three quintessential capabilities of MLLMs for FGVR, including object information extraction, category knowledge reserve, object-category alignment, and position of the root cause as a misalignment problem. To address this issue, we present Finedefics, an MLLM that enhances the model's FGVR capability by incorporating informative attribute descriptions of objects into the training phase. We employ contrastive learning on object-attribute pairs and attribute-category pairs simultaneously and use examples from similar but incorrect categories as hard negatives, naturally bringing representations of visual objects and category names closer. Extensive evaluations across multiple popular FGVR datasets demonstrate that Finedefics outperforms existing MLLMs of comparable parameter sizes, showcasing its remarkable efficacy. 

<img src="/images/finedefics_2.jpg" alt="Finedefics diagram">

**Links:**
- 📄 arXiv: https://arxiv.org/abs/2501.15140
- 🐙 GitHub: https://github.com/PKU-ICST-MIPL/Finedefics_ICLR2025
