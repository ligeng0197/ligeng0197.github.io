+++
author = "Geng Li, Boyuan Ren, Hongzhi Wang"
title = "EEML: Ensemble Embedded Meta-Learning"
date = "2022-10-31"
conference = "WISE 2022"
description = "Guide to emoji usage in Hugo"
tags = [
    "Meta-learning",
]
+++

<img src="/images/eeml.png" alt="EEML diagram">
<!-- <img class="avatar" src="images/avatar.jpg" alt="avatar"> -->

**Authors:** <u>Geng Li</u>, Boyuan Ren, Hongzhi Wang

**Abstract:** To accelerate learning process with few samples, meta-learning resorts to prior knowledge from previous tasks. However, the inconsistent task distribution and heterogeneity is hard to be handled through a global sharing model initialization. In this paper, based on gradient-based meta-learning, we propose an ensemble embedded meta-learning algorithm (EEML) that explicitly utilizes multi-model-ensemble to organize prior knowledge into diverse specific experts. We rely on a task embedding cluster mechanism to deliver diverse tasks to matching experts in training process and instruct how experts collaborate in test phase. As a result, the multi experts can focus on their own area of expertise and cooperate in upcoming task to solve the task heterogeneity. The experimental results show that the proposed method outperforms recent state-of-the-arts easily in few-shot learning problem, which validates the importance of differentiation and cooperation.

<!-- <img src="/images/method.svg" alt="DyFo visual search mechanism diagram"> -->

**Links:**
- 📄 Paper: https://dl.acm.org/doi/10.1007/978-3-031-20891-1_31
