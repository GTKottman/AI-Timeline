# Stanford s1 paper shows test-time scaling with 1,000 examples

- **Date:** 2025-01-31
- **Who:** Stanford University and collaborators (Niklas Muennighoff et al.)
- **Type:** paper

The paper "s1: Simple test-time scaling" builds s1K, a curated set of 1,000 reasoning questions chosen for difficulty, diversity and quality. It adds budget forcing, which stops the model's thinking early or extends it with "Wait" tokens to control test-time compute. The authors report that fine-tuning took about 26 minutes on 16 H100 GPUs, and that the full 59K pool gave no substantial gain over the 1K selection.

## Sources
- https://arxiv.org/abs/2501.19393
