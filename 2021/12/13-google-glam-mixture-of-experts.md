# Google publishes GLaM, a 1.2-trillion-parameter mixture-of-experts model

- **Date:** 2021-12-13
- **Who:** Google Research (Du et al.)
- **Type:** model

Google introduced GLaM (arXiv 2112.06905), a sparse mixture-of-experts language model with up to 1.2 trillion total parameters, about seven times GPT-3's size. Each token is routed to two of 64 experts per layer, so roughly 8% of the weights run per token, and the paper reported about a third of GPT-3's training energy. GLaM beat GPT-3 on zero-, one- and few-shot results across 29 NLP benchmarks. It showed that sparse scaling could cut cost for very large models. The exact December day was not confirmed; the paper was posted in December 2021.

## Sources
- https://arxiv.org/pdf/2112.06905
- https://analyticsindiamag.com/google-releases-new-language-model-that-kicks-gpt-3s-butt
