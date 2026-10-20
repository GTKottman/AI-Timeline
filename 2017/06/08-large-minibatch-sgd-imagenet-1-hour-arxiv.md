# Accurate, Large Minibatch SGD: ImageNet training in one hour (arXiv)

- **Date:** 2017-06-08
- **Who:** Priya Goyal, Kaiming He and co-authors (Facebook)
- **Type:** paper

The paper "Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour" (arXiv 1706.02677) showed ResNet-50 trained with minibatches of 8,192 images on 256 GPUs in about an hour without accuracy loss. The method combined a linear learning-rate scaling rule with a warmup phase, and the authors reported about 90% scaling efficiency from 8 to 256 GPUs. It mattered because it made large-scale distributed training practical and became a standard recipe for data-parallel training.

## Sources
- https://arxiv.org/abs/1706.02677
- https://ar5iv.arxiv.org/html/1706.02677
