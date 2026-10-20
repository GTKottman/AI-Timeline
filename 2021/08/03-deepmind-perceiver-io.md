# DeepMind releases Perceiver IO general architecture

- **Date:** 2021-08-03
- **Who:** DeepMind (Andrew Jaegle, Daniel Zoran, Oriol Vinyals and others)
- **Type:** research

DeepMind published Perceiver IO, a general architecture for structured inputs and outputs, with an arXiv paper (2107.14795) and an August 3, 2021 blog post. The original Perceiver could only produce simple outputs such as classification; Perceiver IO uses a small latent array with a new decoding procedure to scale to large, structured outputs. It matched or beat Transformer baselines on BERT-style GLUE tasks without input tokenization and set state of the art on Sintel optical flow. DeepMind open sourced the code.

## Sources
- https://arxiv.org/pdf/2107.14795
- https://deepmind.google/blog/building-architectures-that-can-handle-the-worlds-data/
