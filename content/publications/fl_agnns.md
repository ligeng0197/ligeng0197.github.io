+++
author = "Chunnan Wang, Bozhou Chen, Geng Li, Hongzhi Wang"
title = "Automated Graph Neural Network Search Under Federated Learning Framework"
date = "2023-10-01"
conference = "TKDE 2023"
description = "Guide to emoji usage in Hugo"
tags = [
    "AutoML",
]
+++

<img src="/images/fl_agnns.jpg" alt="FL_AGNNs diagram">
<!-- <img class="avatar" src="images/avatar.jpg" alt="avatar"> -->

**Authors:** Chunnan Wang, Bozhou Chen, <u>Geng Li</u>, Hongzhi Wang

**Abstract:** Graph Neural Network (GNN) has achieved great success in the field of graph data processing and analysis, but the design of GNN architecture is difficult and time-consuming. To reduce the development cost of GNNs, recently, some GNN Neural Architecture Search (GNN NAS) techniques are presented for the automatic design of GNN architectures. These techniques bring great convenience to the use of GNN, but cannot be applied to the federated learning scenarios. They only consider the single-source graph dataset, while failing to deal with the distributed and private graph datasets, which limits their applications. To address this shortcoming, in this paper we propose FL-AGNNS, an efficient GNN NAS algorithm which enables distributed agents to cooperatively design powerful GNN models while keeping personal information on local devices. FL-AGNNS designs a novel federated evolutionary optimization strategy. This strategy can fully consider the GNN architectures favored by each client, thus recommend GNN architectures that perform well in multiple datasets. In additions, FL-AGNNS applies the GNN super-network, a weight sharing strategy, to speed up the evaluation of GNN models during the search phase. Extensive experimental results show that FL-AGNNS can recommend better GNN models in short time under the federated learning framework, surpassing the state-of-the-arts GNN models.

<img src="/images/fl_agnns_2.jpg" alt="DyFo visual search mechanism diagram">

**Links:**
- 📄 Paper: https://ieeexplore.ieee.org/abstract/document/10056291
- 🐙 GitHub: https://github.com/21S003018/FL-AGCNS
