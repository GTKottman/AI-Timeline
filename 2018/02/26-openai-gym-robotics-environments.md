# OpenAI adds robotics environments to Gym

- **Date:** 2018-02-26
- **Who:** OpenAI (Matthias Plappert et al.)
- **Type:** software

OpenAI added a set of simulated robotics environments to OpenAI Gym, with eight tasks split between a Fetch arm (push, slide, pick and place) and a Shadow Dexterous Hand (in-hand manipulation). All tasks use sparse binary rewards in a multi-goal reinforcement learning setting, with a Baselines implementation of Hindsight Experience Replay, and run on the MuJoCo physics engine. It was published alongside a technical report asking researchers to tackle the challenges. It mattered because it gave RL researchers standard, physically realistic manipulation benchmarks inside a widely used toolkit.

## Sources
- https://arxiv.org/abs/1802.09464
- https://openai.com/index/multi-goal-reinforcement-learning
- https://www.theregister.co.uk/2018/02/26/openai_gym_robotics/
