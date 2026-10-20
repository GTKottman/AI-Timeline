# Google Research publishes Grasp2Vec, self-supervised robot object representations

- **Date:** 2018-12-11
- **Who:** Google Research (Eric Jang, Coline Devin, Sergey Levine, Vincent Vanhoucke)
- **Type:** research

Google Research explained Grasp2Vec, a method where a robot learns object embeddings from its own grasping attempts without human labels. The idea is that removing an object from a bin should change the scene embedding in a predictable way, so the difference between before and after scenes matches the grasped object. The learned embeddings support object localization and goal-conditioned grasping, letting a policy pick up a user-specified object; the paper appeared on arXiv in November 2018 and at CoRL 2018.

## Sources
- https://ai.googleblog.com/2018/12/grasp2vec-learning-object.html
- https://arxiv.org/pdf/1811.06964
- https://proceedings.mlr.press/v87/jang18a.html
