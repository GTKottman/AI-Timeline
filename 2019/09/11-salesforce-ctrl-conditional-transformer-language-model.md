# Salesforce releases CTRL, a 1.63B-parameter controllable language model

- **Date:** 2019-09-11
- **Who:** Salesforce Research (Nitish Shirish Keskar, Bryan McCann, Lav R. Varshney, Caiming Xiong, Richard Socher)
- **Type:** paper

CTRL is a conditional transformer language model with 1.63 billion parameters, trained on roughly 140 GB of text. It conditions generation on control codes (style, domain, dates, entities, topics) that come from structure already present in raw text, so the model can be steered without labeled data. The authors also released pretrained weights, and the paper showed that control codes can help estimate which training sources most likely produced a given sequence. It mattered as an early large, openly released example of controllable text generation.

## Sources
- https://arxiv.org/abs/1909.05858
- https://ar5iv.labs.arxiv.org/html/1909.05858
- https://paperswithcode.co/paper/1909.05858
