---
title: "Safety Depth in Large Language Models: A Markov Chain Perspective"
collection: publications
permalink: /publication/2025-12-02-safety-depth
excerpt: '**Ching-Chia Kao**, Chia-Mu Yu, Chun-Shien Lu, Chu-Song Chen'
date: 2025-12-02
venue: 'NeurIPS'
paperurl: 'https://openreview.net/forum?id=tu3P6KSHGN'
---

Large Language Models (LLMs) are increasingly adopted in high-stakes scenarios, yet their safety mechanisms often remain fragile: simple jailbreak prompts or even benign fine-tuning can bypass internal safeguards. We introduce the notion of *safety depth*, a designated output position where the model refuses to generate harmful content. Leveraging the equivalence between autoregressive language models and Markov chains, we derive the first theoretical result on identifying the optimal safety depth, and propose a cyclic group augmentation strategy that improves safety scores across six LLMs. Our analysis further reveals a fundamental interaction between alignment depth and ensemble width, indicating that broader ensembles can compensate for shallower alignments.

[arXiv](https://arxiv.org/abs/2502.00669) · [OpenReview](https://openreview.net/forum?id=tu3P6KSHGN)
