# EfficientNetV2: Smaller Models and Faster Training

- **Date:** 2021-04-01
- **Who:** Google Research, Brain Team (Mingxing Tan, Quoc V. Le)
- **Type:** model

Google posted EfficientNetV2 to arXiv on 1 April 2021. It combines training-aware neural architecture search with model scaling and adds new blocks such as Fused-MBConv, so models train much faster and are up to 6.8x smaller than earlier networks. Progressive learning raises image size during training and adjusts regularization to keep accuracy. With ImageNet21k pretraining it reported 87.3% ImageNet top-1, beating ViT while training 5x to 11x faster on the same compute. The code went into Google's AutoML repository and the paper was published at ICML 2021.

## Sources
- https://arxiv.org/pdf/2104.00298v2
- https://research.google/pubs/efficientnetv2-smaller-models-and-faster-training/
