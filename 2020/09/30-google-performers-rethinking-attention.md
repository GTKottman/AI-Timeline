# Google introduces Performers: linear-complexity transformers (FAVOR+)

- **Date:** 2020-09-30
- **Who:** Google, DeepMind and University of Cambridge (Krzysztof Choromanski and 12 co-authors)
- **Type:** paper

The arXiv paper "Rethinking Attention with Performers" introduced FAVOR+, a way to approximate softmax attention with random features so that transformer cost grows linearly with sequence length instead of quadratically. The approach can be applied to protein sequence modelling and other long-sequence tasks without changing the rest of the architecture. It was later accepted as an oral at ICLR 2021, and Google's blog covered it in October 2020.

## Sources
- https://arxiv.org/abs/2009.14794
- https://research.google/blog/2020/10
