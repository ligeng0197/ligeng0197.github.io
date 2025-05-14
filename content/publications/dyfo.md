+++
author = "Geng Li, Jinglin Xu, Yunzhen Zhao, Yuxin Peng"
title = "DyFo: A Training-Free Dynamic Focus Visual Search for Enhancing LMMs in Fine-Grained Visual Understanding"
date = "2025-04-21"
conference = "CVPR 2025 (Highlight)"
description = "Guide to emoji usage in Hugo"
tags = [
    "MLLMs/LMMs",
    "Fine-grained perception"
]
+++

<img src="/images/dyfo.jpg" alt="DyFo visual search mechanism diagram">
<!-- <img class="avatar" src="images/avatar.jpg" alt="avatar"> -->

**Authors:** <u>Geng Li</u>, Jinglin Xu, Yunzhen Zhao, Yuxin Peng

**Abstract:** Humans can effortlessly locate desired objects in cluttered environments, relying on a cognitive mechanism known as visual search to efficiently filter out irrelevant information and focus on task-related regions. Inspired by this process, we propose Dyfo (Dynamic Focus), a training-free dynamic focusing visual search method that enhances fine-grained visual understanding in large multimodal models (LMMs). Unlike existing approaches which require additional modules or data collection, Dyfo leverages a bidirectional interaction between LMMs and visual experts, using a Monte Carlo Tree Search (MCTS) algorithm to simulate human-like focus adjustments. This enables LMMs to focus on key visual regions while filtering out irrelevant content, without introducing additional training caused by vocabulary expansion or the integration of specialized localization modules. Experimental results demonstrate that Dyfo significantly improves fine-grained visual understanding and reduces hallucination issues in LMMs, achieving superior performance across both fixed and dynamic resolution models.

<img src="/images/method.svg" alt="DyFo visual search mechanism diagram">

**Links:**
- 📄 arXiv: https://arxiv.org/abs/2504.14920
- 🐙 GitHub: https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025
