# An Empirical Study of Training Self-Supervised Vision Transformers (MoCo v3)

- **Date:** 2021-04-05
- **Who:** Facebook AI Research (Xinlei Chen, Saining Xie, Kaiming He)
- **Type:** paper

Facebook AI Research posted this paper on 5 April 2021, presenting MoCo v3, a contrastive self-supervised method that trains Vision Transformers without labels. It is an incremental step over MoCo v1 and v2 that aims for simplicity, accuracy and scalability. The authors found that training instability often hides behind apparently good results and proposed a fixed random patch projection trick to reduce it. Code and a PyTorch re-implementation were released, and the paper was published at ICCV 2021.

## Sources
- https://arxiv.org/pdf/2104.02057
