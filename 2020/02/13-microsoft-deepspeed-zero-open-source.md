# Microsoft open-sources DeepSpeed with ZeRO optimizer

- **Date:** 2020-02-13
- **Who:** Microsoft Research (AI at Scale)
- **Type:** software

Microsoft released DeepSpeed, an open-source PyTorch-compatible library for large-scale distributed training. It included ZeRO (Zero Redundancy Optimizer), which cuts optimizer-state memory per GPU so models of about 100 billion parameters can train on current clusters. Microsoft said it reached several times the throughput of the best prior system. The same technology trained Turing-NLG (17 billion parameters). The announcement blog is dated February 13, 2020.

## Sources
- https://www.microsoft.com/en-us/research/blog/zero-deepspeed/
- https://www.deepspeed.ai/2020/02/13/release.html
