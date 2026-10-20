# Facebook AI publishes MoCo, momentum contrast for visual self-supervised learning

- **Date:** 2019-11-13
- **Who:** Facebook AI Research (Kaiming He, Haoqi Fan, Yuxin Wu, Saining Xie, Ross Girshick)
- **Type:** research

MoCo treats contrastive learning as dictionary lookup, using a queue of negative keys and a momentum-updated encoder so the dictionary stays large and consistent. It produced competitive ImageNet linear-evaluation results without labels. Its bigger claim was transfer: features pretrained with MoCo beat supervised ImageNet pretraining on seven detection and segmentation tasks. Official code was released on GitHub, and MoCo became a standard baseline for self-supervised vision.

## Sources
- https://arxiv.org/abs/1911.05722
- https://paperswithcode.co/paper/1911.05722
- https://github.com/facebookresearch/moco
