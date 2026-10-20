# Google's AutoAugment learns image augmentation policies with reinforcement learning

- **Date:** 2018-05-24
- **Who:** Google Brain (Ekin D. Cubuk, Barret Zoph, Dandelion Mane, Vijay Vasudevan, Quoc V. Le)
- **Type:** research

The AutoAugment paper, posted to arXiv on May 24, 2018, uses reinforcement learning to search for data augmentation policies rather than relying on hand-designed image transformations. Each policy is built from sub-policies that chain two image operations, and the search keeps the policy that gives the best validation accuracy. The ImageNet policy reached 83.5% top-1 accuracy, reported as 0.4 points above the previous best, and it transferred to other image datasets. Google's AI blog covered the work in June 2018, and the paper was later published at CVPR 2019.

## Sources
- https://arxiv.org/abs/1805.09501v1
- https://ai.googleblog.com/2018/06/improving-deep-learning-performance.html
