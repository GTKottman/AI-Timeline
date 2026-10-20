# DeepSeek releases DeepSeek-OCR, which compresses text into vision tokens

- **Date:** 2025-10-20
- **Who:** DeepSeek
- **Type:** model

DeepSeek released DeepSeek-OCR as an open-source model that tests optical compression: long text is rendered as an image and decoded from a small number of vision tokens. The paper reports about 97% decoding precision at up to 10x compression, falling to about 60% at 20x. The model has a SAM and CLIP encoder and a 3-billion-parameter mixture-of-experts decoder. Coverage says it can process more than 200,000 pages a day on one A100-40G GPU. vLLM support followed on October 23.

## Sources
- https://technode.com/2025/10/21/deepseek-releases-new-ocr-model-capable-of-generating-200000-pages-daily-on-a-single-gpu
- https://intuitionlabs.ai/articles/deepseek-ocr-optical-compression
- https://academy.dair.ai/papers/deepseek-ocr
