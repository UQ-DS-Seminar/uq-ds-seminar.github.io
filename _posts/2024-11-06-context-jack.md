---
layout: post
title: "No.24-13 Contextual Document Embeddings"
author: RQ
categories: [Cornell University]
image: assets/images/speakers/jack.png
tags: [GNN]
date: 2024-11-2
display-date: 2024-11-06
comments: True
---

Dense document embeddings are central to neural retrieval. The dominant paradigm is to train and construct embeddings by running encoders directly on individual documents. In this work, we argue that these embeddings, while effective, are implicitly out-of-context for targeted use cases of retrieval, and that a contextualized document embedding should take into account both the document and neighboring documents in context - analogous to contextualized word embeddings. We propose two complementary methods for contextualized document embeddings: first, an alternative contrastive learning objective that explicitly incorporates the document neighbors into the intra-batch contextual loss; second, a new contextual architecture that explicitly encodes neighbor document information into the encoded representation. Results show that both methods achieve better performance than biencoders in several settings, with differences especially pronounced out-of-domain. We achieve state-of-the-art results on the MTEB benchmark with no hard negative mining, score distillation, dataset-specific instructions, intra-GPU example-sharing, or extremely large batch sizes. Our method can be applied to improve performance on any contrastive learning dataset and any biencoder.

[arXiv Preprint: Contextual Document Embeddings](https://arxiv.org/abs/2410.02525)

## Speaker Bio

Jack (John) Morris is a PhD student at Cornell University and researcher at Meta AI (previously FAIR). Before joining Cornell, he was a Google AI Resident. He works on understanding and improving text embeddings.

## More Details

- When: Wed 06 Nov 2024, at 11:00 am - 12:00 pm (Brisbane time)
- Speaker: Jack (John) Morris (Cornell University & Meta AI)
- Host: Ruihong Qiu
- Venue: Online
- Zoom: [https://uqz.zoom.us/j/87626530209](https://uqz.zoom.us/j/87626530209) [[Recording]](https://uqz.zoom.us/rec/share/uMPN-4c4Obv72-H6rQwFdnZ9oKHB5lg-QELYZEqnkbhcn9a_PhYIV9xYpUPV3HMV.B6aQsxV71RA56dmQ)
