# DeepMind publishes IMPALA, a scalable distributed deep RL agent

- **Date:** 2018-02-05
- **Who:** DeepMind
- **Type:** paper

DeepMind posted the IMPALA paper (Importance Weighted Actor-Learner Architectures) to arXiv. The agent decouples acting from learning so one set of parameters can handle many tasks and scale to thousands of machines without losing data efficiency. Its V-trace off-policy correction keeps learning stable when actors run behind the learner. The authors reported results on DMLab-30 and Atari-57 and released the code as scalable_agent; the paper was later published at ICML 2018.

## Sources
- https://arxiv.org/pdf/1802.01561
- https://research.google/pubs/impala-scalable-distributed-deep-rl-with-importance-weighted-actor-learner-architectures/
- https://github.com/deepmind/scalable_agent
