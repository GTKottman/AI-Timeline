# vLLM: open-source LLM serving with PagedAttention

- **Date:** 2023-06-20
- **Who:** UC Berkeley (Sky Computing Lab) with LMSYS
- **Type:** software

vLLM was released publicly as an open-source inference and serving library. Its PagedAttention algorithm manages attention key-value memory in pages, and the launch post claimed up to 24x higher throughput than Hugging Face Transformers with no model changes. It had already served LMSYS Vicuna and Chatbot Arena, and it became a standard open-source engine for serving LLMs.

## Sources
- https://vllm.ai/blog/2023-06-20-vllm
- https://pypi.org/project/vllm/0.2.2
