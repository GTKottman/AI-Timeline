# ULMFiT: Universal Language Model Fine-tuning for Text Classification

- **Date:** 2018-01-18
- **Who:** Jeremy Howard, Sebastian Ruder
- **Type:** paper

The paper proposed ULMFiT, a transfer learning method for NLP. A language model is pretrained on a large general corpus, then fine-tuned on the target data with techniques such as discriminative learning rates and gradual unfreezing before a classifier is trained. The authors reported lower error than prior state of the art on six text classification tasks, and that with about 100 labeled examples it matched training from scratch on 100 times more data. It mattered because it showed the ImageNet-style pretrain-then-fine-tune recipe working for text, which later fed into the wave of pretrained language models. Code and pretrained models were released.

## Sources
- https://arxiv.org/abs/1801.06146
- https://acl2018.org/paper/107
