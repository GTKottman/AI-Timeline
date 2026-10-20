# Google publishes GShard, scaling giant models with conditional computation

- **Date:** 2020-06-30
- **Who:** Google
- **Type:** paper

The arXiv paper "GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding" introduced a module and XLA compiler extension for annotating how large models are split across accelerators. Using sparsely-gated mixture-of-experts layers, the authors scaled a multilingual translation Transformer past 600 billion parameters and trained it in 4 days on 2048 TPU v3 chips. It showed that sparse conditional computation could be trained at very large scale.

## Sources
- https://arxiv.org/abs/2006.16668
