---
layout: post
title: "No.26-05 No-Regret Self-Improvement: A Unified Game-Theoretic Formulation for AI Self-Improvement"
author: RQ
categories: [LLM]
image: assets/images/speakers/null.jpeg
tags: [LLM]
date: 2026-10-05
display-date: 2026-10-07
comments: True
---

Ensuring that AI systems improve consistently under iterative feedback is a central challenge in AI self-improvement. This talk presents a unified game-theoretic formulation that connects reinforcement learning and self-play through regularized no-regret policy updates, with applications to language model alignment and reasoning.

For alignment, we introduce Regularized Self-Play Policy Optimization (RSPO), which optimizes pairwise preferences directly and accommodates non-transitive preference structures. Based on generalized magnetic mirror descent, RSPO supports a broad class of regularizers and provides convergence guarantees to a regularized Nash equilibrium under appropriate assumptions. For reasoning in diffusion language models, we interpret reinforcement learning as approximation of a no-regret policy target. This perspective motivates wd1, a weighted policy optimization method, and Guided Denoiser Self-Distillation (GDSD), which distills an advantage-guided denoising teacher without requiring sequence likelihood ratios. Empirical results demonstrate improved alignment performance and reasoning capabilities, alongside gains in training efficiency and stability. We conclude by discussing the implications for recursive self-improvement and the remaining challenges associated with feedback quality, reward hacking, and safety in agentic environments.

## Speaker Bio

Xiaohang Tang is a PhD candidate in Statistical Science at University College London, supervised by Ilija Bogunovic, and a Student Researcher at Google DeepMind. His research focuses on reinforcement learning, game theory, and self-improving AI systems, with particular interests in self-play for language model alignment and reinforcement learning for reasoning in diffusion language models. At Google DeepMind, he works on automated research and scientific discovery using AlphaEvolve, with a focus on multi-agent systems. His research has appeared at ICML, NeurIPS, and ICLR.

## More Details

- When: Wed 7 Oct 2026, at 4:30 pm - 5:30 pm (Brisbane time)
- Speaker: Xiaohang Tang (University College London & Google DeepMind)
- Host: Ruihong Qiu
- Coordinator: Zijian Wang
- Zoom: [https://uqz.zoom.us/j/83507587750](https://uqz.zoom.us/j/83507587750) [[Recording]](https://uqz.zoom.us/j/83507587750)
