# ELECTRA: pretraining text encoders as discriminators

- **Date:** 2020-03-23
- **Who:** Stanford University and Google Brain (Clark, Luong, Le, Manning)
- **Type:** paper

The arXiv paper "ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators" introduced replaced-token detection, where a small generator swaps input tokens and a discriminator learns which ones were replaced. It was more sample-efficient than masked language modeling and matched RoBERTa and XLNet at lower compute. It became a widely used efficient pretraining recipe for language encoders.

## Sources
- https://arxiv.org/abs/2003.10555
