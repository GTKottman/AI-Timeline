# ELMo paper introduces deep contextualized word representations

- **Date:** 2018-02-15
- **Who:** Matthew E. Peters and colleagues at the Allen Institute for AI and the University of Washington
- **Type:** paper

The ELMo paper, "Deep contextualized word representations," was posted to arXiv. It gives each word a vector computed from all layers of a bidirectional language model, so the same word gets different vectors in different sentences. Downstream models learn a task-specific weighted mix of those layers. The authors reported clear gains across six NLP tasks, including question answering, textual entailment and sentiment analysis, and the paper was published at NAACL 2018. It helped set up the pretrain-then-fine-tune approach that later transformer models built on.

## Sources
- https://arxiv.org/pdf/1802.05365
- https://paperswithcode.co/paper/1802.05365
