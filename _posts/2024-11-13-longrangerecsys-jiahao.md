---
layout: post
title: "No.24-14 Long-Range Meets Scalability: Unveiling a Linear-Time Graph Neural Network for Recommendation at Scale"
author: RQ
categories: [Pennsylvania State University]
image: assets/images/speakers/zjh.jpg
tags: [RecSys]
date: 2024-11-6
display-date: 2024-11-13
comments: True
---

Recommender systems play a central role in shaping our daily digital experiences, yet achieving both scalability and expressive power remains a significant challenge. While Graph Neural Networks (GNNs) excel at capturing long-range user-item relationships, their heavy computational demands often make them less practical at large scales, where simpler models like Matrix Factorization (MF) and Deep Neural Networks (DNNs) are more commonly used.

In this talk, I will introduce Linear-Time Graph Neural Network (LTGNN), a breakthrough approach designed to bridge the scalability gap between GNNs and simpler methods without sacrificing GNNs' unique ability to capture distant dependencies. Through a fixed-point formulation, LTGNN reduces the number of GNN layers to one by reusing historical fixed-point computations, preserving a large "receptive field" on graphs. Additionally, a variance reduction mechanism accelerates neighbor aggregation, achieving high accuracy with a minimal number of sampled neighbors. Together, these two innovations enable LTGNN to operate at near-MF complexity, as verified by extensive empirical results.

While this talk covers our recent [WWW 2024 paper](https://dl.acm.org/doi/abs/10.1145/3589334.3645486), it also goes beyond by introducing new theoretical insights, deeper discussions, and foundational design principles. This presentation will highlight a promising direction for scaling up GNNs effectively in recommendation systems.

## Speaker Bio

Jiahao Zhang is currently a first-year PhD student at the Pennsylvania State University, advised by Prof. Suhang Wang. He was previously has an M.Phil. student at The Hong Kong Polytechnic University, advised by Prof. Wenqi Fan and Prof. Qing Li. He is interested in the scalability and trustworthiness of graph neural networks, as well as the application of graph neural networks on recommender systems.

## More Details

- When: Wed 13 Nov 2024, at 1 - 2 pm (Brisbane time)
- Speaker: Jiahao Zhang (Pennsylvania State University)
- Host: Ruihong Qiu
- Venue: Online
- Zoom: [https://uqz.zoom.us/j/87200611980](https://uqz.zoom.us/j/87200611980) [[Recording]](https://uqz.zoom.us/j/87200611980)
