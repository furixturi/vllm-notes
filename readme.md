# vLLM on Azure Machine Learning

This repo includes various notes and exercises about running vLLM on Azure Machine Learning.

vLLM is a fast and easy-to-use library for LLM inference and serving. Key features:

- State-of-the-art serving throughput
- Efficient management of attention key and value memory with **PagedAttention**
- Continuous batching of incoming requests
- Fast model execution with CUDA/HIP graph
- Quantizations: [GPTQ](https://arxiv.org/abs/2210.17323), [AWQ](https://arxiv.org/abs/2306.00978), INT4, INT8, and FP8.
- Optimized CUDA kernels, including integration with FlashAttention and FlashInfer.
- Speculative decoding
- Chunked prefill

## References
- [Github repo](https://github.com/vllm-project/vllm)
- [Official doc](https://docs.vllm.ai/en/latest/)