# Perceiver: General Perception with Iterative Attention

- **Date:** 2021-03-04
- **Who:** DeepMind (Andrew Jaegle et al.)
- **Type:** paper

DeepMind submitted the Perceiver paper to arXiv on 4 March 2021. The model is a Transformer that projects any input (images, audio, point clouds, video) into a small fixed latent array and attends to the raw input iteratively, so cost does not grow with the square of input size. It reached ResNet-50 and ViT-level ImageNet accuracy without 2D convolutions, attending directly to 50,000 pixels. The paper was later published at ICML 2021, and it led to the Perceiver IO follow-up.

## Sources
- https://arxiv.org/abs/2103.03206
- https://proceedings.mlr.press/v139/jaegle21a.html
