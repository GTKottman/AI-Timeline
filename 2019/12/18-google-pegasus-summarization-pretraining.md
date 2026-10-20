# Google releases PEGASUS, gap-sentence pre-training for abstractive summarization

- **Date:** 2019-12-18
- **Who:** Google Research; Jingqing Zhang (Imperial College London)
- **Type:** paper

Google researchers posted PEGASUS to arXiv (1912.08777). It pre-trains a large Transformer encoder-decoder by masking important sentences from a document and having the model regenerate them as one output. The authors report state-of-the-art ROUGE on all 12 summarization datasets they tested, and beat earlier state of the art on 6 of those datasets with only 1,000 training examples. It helped make pre-training objectives tailored to a task a standard approach.

## Sources
- https://arxiv.org/pdf/1912.08777v1
- https://huggingface.co/transformers/v3.1.0/model_doc/pegasus.html
