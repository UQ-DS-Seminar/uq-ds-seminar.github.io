---
layout: post
title:  "No.23-10 SEINE: SEgment-based Indexing for NEural Information Retrieval"
author: yadan
categories: [Georgetown University]
image: assets/images/speakers/grace.jpg
tags: [Zoom Webinar,featured]
date: 2022-12-13
display-date: 2023-05-03
comments: True
---
Many early neural Information Retrieval (NeurIR) methods are re-rankers that rely on a traditional first-stage retriever due to expensive query time computations. Recently, representation-based retrievers have gained much attention, which learn query representation and document representation separately, making it possible
to pre-compute document representations offline and reduce the workload at query time. Both dense and sparse representation-based retrievers have been explored. However, these methods focus on finding the representation that best represents a text (aka metric learning), and the actual retrieval function that is responsible
for similarity matching between query and document is kept at a minimum by using dot product. One drawback is that, unlike a traditional term-level inverted index, the index formed by these embeddings cannot be easily re-used by another retrieval method. Another drawback is that keeping the interaction at a minimum hurts
retrieval effectiveness. On the contrary, interaction-based retrievers are known for their better retrieval effectiveness. In this work, we propose a novel SEgment-based Neural Indexing method, SEINE, which provides a general indexing framework that can flexibly support a variety of interaction-based neural retrieval
methods. We emphasize a careful decomposition of common components in existing neural retrieval methods and propose to use
a segment-level inverted index to store the atomic query-document interaction values. Experiments on LETOR MQ2007 and MQ2008
datasets show that our indexing method can accelerate multiple neural retrieval methods up to 28 times faster without sacrificing
much effectiveness.

## Short Bio
Dr. Grace Hui Yang is Associate Professor in Computer Science at Georgetown University, Washington D.C. Dr. Yang is leading the InfoSense (Information Retrieval and Sense-Making) group at Georgetown University. Dr. Yang obtained her Ph.D. from Carnegie Mellon University in 2011. Her current research interests include deep reinforcement learning, interactive agents, search engines, and privacy-preserving information retrieval. Prior to this, she conducted research on question answering, automatic ontology construction, near-duplicate detection, multimedia information retrieval, and opinion and sentiment detection. Dr. Yang's research has been supported by the Defense Advanced Research Projects Agency (DARPA) and the National Science Foundation (NSF). Dr. Yang led the effort for the Text Retrieval Conference (TREC) Dynamic Domain Tracks from 2015 to 2017 and SIGIR privacy-preserving information retrieval workshops from 2014 to 2016 and co-organized the SIGIR Deep Reinforcement Learning Workshops since 2020. Dr. Yang is associate editor for ACM Transactions on Information Systems and served on the editorial board of Information Retrieval Journal from 2014 to 2017. She has actively served as an organizing or program committee member in many top-tier international conferences such as SIGIR, ECIR, ACL, AAAI, ICTIR, CIKM, WSDM, and WWW, and the general co-chair of SIGIR 2024. She is a recipient of the NSF Faculty Early Career Development Program (CAREER) Award and a co-author of the 2016 book “Dynamic Information Retrieval Modeling.”

## More Details
+ When: Wed 3 May 2023, at 10:00 am (GMT+10)
+ Speaker: Dr Grace Hui Yang (Georgetown University)
+ Host: Prof Helen Huang
+ Zoom: [https://uqz.zoom.us/j/82896549343](https://uqz.zoom.us/j/82896549343)




## Zoom Recording
