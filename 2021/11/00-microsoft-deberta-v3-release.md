# Microsoft releases DeBERTaV3 with ELECTRA-style pretraining

- **Date:** 2021-11-00
- **Who:** Microsoft Research (Pengcheng He, Jianfeng Gao, Weizhu Chen)
- **Type:** model

Microsoft released DeBERTaV3, an upgrade to DeBERTa that swaps masked language modelling for ELECTRA-style replaced token detection with gradient-disentangled embedding sharing. The large variant reported 91.5/89.0 on SQuAD 2.0 and 91.8/91.9 on MNLI. Weights were published on Hugging Face under the microsoft namespace, and the model became a widely used encoder for NLU fine-tuning. The exact day is unconfirmed: Synced Review's 23 Nov 2021 article says "this week", and the arXiv ID is 2111.09543.

## Sources
- https://syncedreview.com/2021/11/23/deepmind-podracer-tpu-based-rl-frameworks-deliver-exceptional-performance-at-low-cost-150/
- https://huggingface.co/microsoft/deberta-v3-small
