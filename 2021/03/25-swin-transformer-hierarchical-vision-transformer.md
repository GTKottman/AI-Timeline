# Swin Transformer: Hierarchical Vision Transformer using Shifted Windows

- **Date:** 2021-03-25
- **Who:** Microsoft Research Asia (Ze Liu et al.)
- **Type:** paper

Microsoft Research Asia posted the Swin Transformer paper to arXiv on 25 March 2021. It builds a hierarchical vision transformer that computes self-attention inside shifted local windows, which keeps cost roughly linear in image size. That makes transformers usable as a general backbone for dense tasks such as detection and segmentation, not only image classification. The v1 paper reported 86.4% top-1 on ImageNet-1K, 58.7 box AP on COCO test-dev and 53.5 mIoU on ADE20K val; the work later won the ICCV 2021 Marr Prize.

## Sources
- https://arxiv.org/abs/2103.14030
- https://deepai.org/publication/swin-transformer-hierarchical-vision-transformer-using-shifted-windows
