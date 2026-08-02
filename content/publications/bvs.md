+++
author = "Geng Li, Yuxin Peng"
title = "BVS: Bayesian Visual Search with Multimodal Large Language Model for Fine-grained Perception"
date = "2026-07-03"
conference = "ICML 2026"
description = "A Bayesian visual search framework for fine-grained perception in ultra-high-resolution images."
tags = [
    "MLLMs/LMMs",
    "Fine-grained perception",
    "Visual reasoning"
]
+++

**Authors:** <u>Geng Li</u>, Yuxin Peng

**Abstract:** While Multimodal Large Language Models (MLLMs) demonstrate impressive general capabilities, they struggle with fine-grained perception in ultra-high-resolution (UHR) images, particularly for tiny objects in cluttered scenes. Existing methods face a dilemma: they either rely on inefficient prior-free scanning, or depend on static prior-driven heuristics that lack posterior correction to rectify initial model biases. To address this, we propose BVS (Bayesian Visual Search), a framework that formulates perception as a global optimization problem over a continuous spatial-scale manifold. Specifically, BVS bridges prior guidance with posterior correction: it utilizes an early-stop attention rollout of MLLM to construct reasoning-aware priors, while employing a scale-aware non-stationary kernel and GP-UCB to dynamically rectify noise and recover missing information in the prior through iterative local observations. We provide theoretical guarantees via sub-linear regret bounds, and extensive experiments demonstrate that BVS significantly outperforms state-of-the-art baselines with a superior trade-off between accuracy and efficiency.

**Links:**
- 📄 arXiv: https://arxiv.org/abs/2607.03184
- 🐙 GitHub: https://github.com/PKU-ICST-MIPL/BVS_ICML2026
