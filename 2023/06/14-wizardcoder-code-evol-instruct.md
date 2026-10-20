# WizardCoder: code LLM tuned with Code Evol-Instruct

- **Date:** 2023-06-14
- **Who:** WizardLM team (Microsoft and collaborators)
- **Type:** model

WizardCoder adapted Evol-Instruct to code: it evolved the Code Alpaca dataset with coding-specific heuristics (including erroneous code as adversarial samples and time and space complexity) and fine-tuned StarCoder on the result. The paper reported that the 15B model beat Claude and Bard on HumanEval and HumanEval+. Code, weights and data were published, making it a widely used open code model in mid-2023.

## Sources
- https://arxiv.org/pdf/2306.08568
- https://www.microsoft.com/en-us/research/publication/wizardcoder-empowering-code-large-language-models-with-evol-instruct/
