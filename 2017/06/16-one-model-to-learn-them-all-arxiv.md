# One Model To Learn Them All (MultiModel) on arXiv

- **Date:** 2017-06-16
- **Who:** Google Brain and collaborators (Łukasz Kaiser, Aidan N. Gomez, Noam Shazeer, Ashish Vaswani, Niki Parmar, Llion Jones, Jakob Uszkoreit)
- **Type:** paper

This arXiv paper (1706.05137) trains one model jointly on ImageNet, several translation tasks, COCO image captioning, a speech recognition corpus, and English parsing. Its architecture combines convolutional blocks, attention, and sparsely-gated mixture-of-experts layers, with different blocks serving different tasks. It was submitted the same month as the Transformer paper and showed early that a single network could share parameters across very different domains.

## Sources
- https://arxiv.org/abs/1706.05137v1
- https://research.google/pubs/one-model-to-learn-them-all/
