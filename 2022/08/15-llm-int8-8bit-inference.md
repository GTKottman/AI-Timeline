# LLM.int8(): 8-bit matrix multiplication at scale

- **Date:** 2022-08-15
- **Who:** University of Washington and Hugging Face researchers
- **Type:** research

LLM.int8() is a mixed-precision method that runs most transformer matrix multiplications in 8-bit and sends outlier features through a separate 16-bit path. It cut inference memory for models above 6.7B parameters roughly in half without hurting results, making large models run on fewer GPUs.

## Sources
- https://arxiv.org/abs/2208.07339
