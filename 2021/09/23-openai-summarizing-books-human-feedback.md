# OpenAI summarizes whole books with recursive human-feedback GPT-3

- **Date:** 2021-09-23
- **Who:** OpenAI (Jeff Wu, Long Ouyang, Daniel Ziegler, Nisan Stiennon, Ryan Lowe, Jan Leike, Paul Christiano)
- **Type:** research

OpenAI published "Recursively Summarizing Books with Human Feedback" (arXiv 2109.10862) and a blog post on September 23, 2021. A GPT-3 model fine-tuned on human comparisons summarizes a book by condensing sections and then condensing the summaries, repeating until one summary remains. The authors report that the best model's summaries occasionally match human-written quality, in roughly 5% of books, and that it sets state of the art on BookSum. The work is an early example of scalable human oversight for hard tasks.

## Sources
- https://arxiv.org/pdf/2109.10862
- https://openai.com/index/summarizing-books/
