# LAION-400M open dataset of 400 million CLIP-filtered image-text pairs

- **Date:** 2021-11-03
- **Who:** LAION (Christoph Schuhmann, Richard Vencu, Romain Beaumont, Robert Kaczmarczyk, Clayton Mullis, Aarush Katta, Theo Coombes, Jenia Jitsev, Aran Komatsuzaki)
- **Type:** dataset

LAION-400M was posted to arXiv on 3 November 2021 as an open dataset of 400 million image-text pairs. Pairs were filtered with OpenAI's CLIP model, dropping those below cosine similarity 0.3, and the release included CLIP embeddings and kNN indices for similarity search. The pairs come from Common Crawl web pages crawled from 2014 to 2021. It gave open research groups a large image-text training corpus outside big-lab data pipelines.

## Sources
- https://arxiv.org/abs/2111.02114v1
- https://www.tensorflow.org/datasets/catalog/laion400m?hl=ja
