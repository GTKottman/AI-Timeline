# OpenAI and collaborators publish Random Network Distillation for exploration

- **Date:** 2018-10-30
- **Who:** OpenAI (Yuri Burda, Harrison Edwards, Amos Storkey, Oleg Klimov)
- **Type:** research

OpenAI published Random Network Distillation (RND), an exploration bonus based on prediction error. A neural network is trained to predict the output of a fixed, randomly initialized network on visited states, and the prediction error serves as a novelty reward. The authors reported the first method to beat average human performance on Montezuma's Revenge without demonstrations or access to the game's internal state, and it sometimes completed the first level. The paper, "Exploration by Random Network Distillation," appeared on arXiv the same month.

## Sources
- https://openai.com/blog/reinforcement-learning-with-prediction-based-rewards/
- https://arxiv.org/pdf/1810.12894
- https://paperswithcode.co/paper/1810.12894
