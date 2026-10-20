# Google CoCa: Contrastive Captioners are Image-Text Foundation Models

- **Date:** 2022-05-04
- **Who:** Google Research (Jiahui Yu, Zirui Wang, Vijay Vasudevan, Legg Yeung, Mojtaba Seyedhosseini, Yonghui Wu)
- **Type:** paper

Google posted CoCa, a single image-text model trained with both a CLIP-style contrastive loss and a captioning loss. Its decoder handles text alone in early layers and attends to images in later ones, letting one model serve classification, retrieval, VQA and captioning. CoCa reported 86.3% zero-shot ImageNet top-1 accuracy, and it was later published in TMLR in 2022.

## Sources
- https://arxiv.org/abs/2205.01917
- https://research.google/pubs/coca-contrastive-captioners-are-image-text-foundation-models/
