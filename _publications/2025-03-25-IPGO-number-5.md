---
title: "IPGO: Indirect Prompt Gradient Optimization on Text-to-Image Generative Models with High Data Efficiency"
collection: publications
category: preprints
permalink: /publication/2025-03-25-IPGO-number-5
excerpt: 'A statistically-informed neural network for eye gaze predictions.'
date: 2025-03-25
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2503.21812'
citation: 'Jianping Ye, Michel Wedel, Kunpeng Zhang'
---

Text-to-Image Diffusion models excel at generating images from text prompts but often exhibit suboptimal alignment with content semantics, aesthetics, and human preferences. To address these limitations, this study proposes a novel parameter-efficient framework, Indirect Prompt Gradient Optimization (IPGO), for prompt-level diffusion model fine-tuning. IPGO enhances prompt embeddings by injecting continuously differentiable embeddings at the beginning and end of the prompt embeddings, leveraging low-rank structures with the flexibility and nonlinearity from rotations. This approach enables gradient-based optimization of injected embeddings under range, orthonormality, and conformity constraints, effectively narrowing the search space, promoting a stable solution, and ensuring alignment between the embeddings of the injected embeddings and the original prompt. Its extension IPGO+ adds a parameter-free cross-attention mechanism on the prompt embedding to enforce dependencies between the original prompt and the inserted embeddings. We conduct extensive evaluations through prompt-wise (IPGO) and prompt-batch (IPGO+) training using three reward models of image aesthetics, image-text alignment, and human preferences across three datasets of varying complexity. The results show that IPGO consistently outperforms SOTA benchmarks, including stable diffusion v1.5 with raw prompts, text-embedding-based methods (TextCraftor), training-based methods (DRaFT and DDPO), and training-free methods (DPO-Diffusion, Promptist, and ChatGPT-4o). Specifically, IPGO achieves a win-rate exceeding 99% in prompt-wise learning, and IPGO+ achieves a comparable, but often better performance against current SOTAs (a 75% win rate) in prompt-batch learning. Moreover, we illustrate IPGO's generalizability and its capability to significantly enhance image quality while requiring minimal data and resources.