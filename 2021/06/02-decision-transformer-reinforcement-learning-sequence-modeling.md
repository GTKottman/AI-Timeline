# Decision Transformer: reinforcement learning as sequence modeling

- **Date:** 2021-06-02
- **Who:** Lili Chen, Kevin Lu, Aravind Rajeswaran, Kimin Lee, Aditya Grover, Michael Laskin, Pieter Abbeel, Aravind Srinivas, Igor Mordatch (UC Berkeley, Google Research and collaborators)
- **Type:** paper

Decision Transformer posted to arXiv (2106.01345) and treats offline reinforcement learning as conditional sequence modeling. A causally masked Transformer is conditioned on a desired return, past states and actions, and generates the actions expected to reach that return. The authors reported results matching or beating model-free offline RL baselines on Atari, OpenAI Gym and Key-to-Door tasks. It was an early sign that large sequence models could replace value-function and policy-gradient machinery in RL; it was later published at NeurIPS 2021.

## Sources
- https://arxiv.org/abs/2106.01345
- https://proceedings.neurips.cc/paper/2021/hash/7f489f642a0ddb10272b5c31057f0663-Abstract.html
