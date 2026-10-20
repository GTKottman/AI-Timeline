# Hindsight Experience Replay for sparse-reward reinforcement learning (arXiv)

- **Date:** 2017-07-05
- **Who:** Marcin Andrychowicz, Filip Wolski, Pieter Abbeel, Wojciech Zaremba and co-authors (OpenAI)
- **Type:** paper

"Hindsight Experience Replay" (arXiv 1707.01495) lets an agent learn from failed attempts by re-labelling each episode with the goal it actually reached, so only sparse binary rewards are needed. It works with any off-policy RL algorithm and was tested on robot-arm pushing, sliding and pick-and-place tasks, with policies trained in simulation transferring to a physical robot. It mattered because it made goal-directed robot learning practical without hand-written reward shaping.

## Sources
- https://arxiv.org/pdf/1707.01495
- https://arxiv.org/abs/1707.01495v2
