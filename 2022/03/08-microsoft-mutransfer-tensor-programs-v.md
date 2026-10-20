# Microsoft µTransfer: tuning huge networks from small proxies

- **Date:** 2022-03-08
- **Who:** Microsoft Research; OpenAI (co-authors)
- **Type:** research

Microsoft Research published µTransfer, a method built on the µP parameterization from the "Tensor Programs V" paper, which lets hyperparameters tuned on a small proxy model carry over to much larger networks. The team tuned a 40-million-parameter proxy and copied the best settings onto the 6.7-billion-parameter GPT-3, using about 7 percent of GPT-3's pretraining compute for the tuning. It mattered because it gave labs a cheap way to tune networks too costly to train more than once, though The Register noted some hyperparameters still need direct tuning.

## Sources
- https://www.sdxcentral.com/press-releases/microsoft-research-expands-the-limits-of-tuning-enormous-neural-networks/
- https://www.theregister.com/2022/03/14/microsoft_openai_mutransfer/
- https://www.microsoft.com/en-us/research/wp-json/wp/v2/posts/823648
