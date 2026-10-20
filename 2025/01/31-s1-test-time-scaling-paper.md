# Stanford s1 paper shows test-time scaling with 1,000 examples

- **Date:** 2025-01-31
- **Who:** Stanford University and collaborators (Niklas Muennighoff et al.)
- **Type:** paper

The paper "s1: Simple test-time scaling" builds s1K, a curated set of 1,000 reasoning questions chosen for difficulty, diversity and quality, with reasoning traces distilled from Gemini Thinking Experimental. It adds budget forcing, which stops the model's thinking early or extends it by appending "Wait", to control test-time compute. The authors fine-tuned Qwen2.5-32B-Instruct on the set, a run that took 26 minutes on 16 H100 GPUs. Model, data and code are open source on GitHub.

## Sources
- https://arxiv.org/abs/2501.19393
