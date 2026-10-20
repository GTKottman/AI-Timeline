# Google publishes Muse text-to-image paper

- **Date:** 2023-01-02
- **Who:** Google Research (Huiwen Chang, Han Zhang, Jose Lezama, Kevin Murphy, William T. Freeman and others)
- **Type:** paper

The paper "Muse: Text-To-Image Generation via Masked Generative Transformers" was submitted to arXiv on 2 January 2023. Muse predicts masked image tokens with a transformer instead of running a diffusion process, and it uses frozen text embeddings from a large language model. The authors report a 900M-parameter model at FID 6.06 on CC3M and a 3B-parameter model at FID 7.88 on zero-shot COCO, with much faster sampling than pixel diffusion models such as Imagen and DALL-E 2. Google did not release the model publicly.

## Sources
- https://arxiv.org/abs/2301.00704
