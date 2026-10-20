# ResMLP: Feedforward networks for image classification with data-efficient training

- **Date:** 2021-05-07
- **Who:** Facebook AI (Touvron et al.)
- **Type:** paper

Facebook AI posted ResMLP to arXiv on 7 May 2021. The image classifier is built only from MLP layers, with one residual sublayer that mixes information across image patches and one that processes each patch's channels. It was trained with heavy augmentation and distillation to reach a good accuracy-to-complexity balance on ImageNet, with no attention and no convolutions. It was one of several 2021 MLP-only vision models, alongside Google's MLP-Mixer, and the authors released code and pretrained checkpoints.

## Sources
- https://arxiv.org/pdf/2105.03404
- https://ar5iv.labs.arxiv.org/html/2105.03404
