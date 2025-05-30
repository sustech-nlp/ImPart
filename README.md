# ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs

The official implementation of the paper [ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs](https://www.arxiv.org/abs/2504.13237).

![overview.pdf](assets/overview.webp)

## Abstract

With the proliferation of task-specific large language models, delta compression has emerged as a method to mitigate the resource challenges of deploying numerous such models by effectively compressing the delta model parameters. Previous delta-sparsification methods either remove parameters randomly or truncate singular vectors directly after singular value decomposition (SVD). However, these methods either disregard parameter importance entirely or evaluate it with too coarse a granularity. In this work, we introduce ImPart, a novel importance-aware delta sparsification approach. Leveraging SVD, it dynamically adjusts sparsity ratios of different singular vectors based on their importance, effectively retaining crucial task-specific knowledge even at high sparsity ratios. Experiments show that ImPart achieves state-of-the-art delta sparsification performance, demonstrating 2× higher compression ratio than baselines at the same performance level. When integrated with existing methods, ImPart sets a new state-of-the-art on delta quantization and model merging.

## Code will be released soon
