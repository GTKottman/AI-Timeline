# Facebook AI publishes BART, a denoising sequence-to-sequence pretraining model

- **Date:** 2019-10-29
- **Who:** Facebook AI (Mike Lewis, Yinhan Liu, Naman Goyal and colleagues)
- **Type:** model

BART pretrains a sequence-to-sequence transformer by corrupting text (shuffling sentences and masking spans) and training it to reconstruct the original. It pairs a bidirectional encoder with an autoregressive decoder, so it works for both understanding and generation. The paper reported parity with RoBERTa on GLUE and SQuAD and new state of the art on abstractive dialogue, question answering and summarization, with gains up to 6 ROUGE. It became one of the standard pretrained models for summarization and text generation.

## Sources
- https://arxiv.org/abs/1910.13461
- https://paperswithcode.co/paper/1910.13461
