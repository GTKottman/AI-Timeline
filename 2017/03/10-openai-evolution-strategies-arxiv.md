# OpenAI: evolution strategies as a scalable alternative to RL (arXiv)

- **Date:** 2017-03-10
- **Who:** Tim Salimans, Jonathan Ho, Xi Chen, Szymon Sidor, Ilya Sutskever (OpenAI)
- **Type:** paper

OpenAI posted "Evolution Strategies as a Scalable Alternative to Reinforcement Learning" (arXiv 1703.03864), showing that a black-box evolution strategy trains policies on MuJoCo and Atari with no backpropagation or value function. Because workers only exchange scalar rewards, it scaled to over a thousand parallel workers, solving 3D humanoid walking in about 10 minutes. It mattered because it made a simple, highly parallel alternative to standard RL a serious option.

## Sources
- https://arxiv.org/abs/1703.03864v2
- https://openai.com/index/evolution-strategies
