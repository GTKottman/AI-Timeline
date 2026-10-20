# Google publishes Reformer, an efficient Transformer for long sequences

- **Date:** 2020-01-13
- **Who:** Google Research; Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya
- **Type:** paper

The Reformer paper (arXiv 2001.04451) cut Transformer attention cost from quadratic to roughly L log L using locality-sensitive hashing. It also used reversible residual layers to store activations once rather than per layer. The authors report quality matching standard Transformers with much lower memory on long sequences. Google's research blog followed on January 16, 2020. It was accepted at ICLR 2020.

## Sources
- https://arxiv.org/abs/2001.04451v2
- https://research.google/blog/reformer-the-efficient-transformer/
