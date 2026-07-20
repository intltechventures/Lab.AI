
# Diffusion Language Models (DLMs)

## Articles

- O'Reilly Radar: The Tokens You Can’t Wait For
  + Text diffusion, the GPU hangover, and the one place parallel generation actually pays off
  + https://www.oreilly.com/radar/the-tokens-you-cant-wait-for/


## Papers 

- Awesome-Large-Language-Diffusion-Models
  + https://github.com/AIDASLab/Awesome-Diffusion-LLM
    * "_A comprehensive list of papers about Large-Language-Diffusion-Models._"


- Large Language Diffusion Models
  + https://arxiv.org/abs/2502.09992
    * "_The capabilities of large language models (LLMs) are widely regarded as relying on autoregressive models (ARMs). We challenge this notion by introducing LLaDA, a diffusion model trained from scratch under the pre-training and supervised fine-tuning (SFT) paradigm. LLaDA employs a forward data masking process and a reverse generation process, parameterized by a Transformer to predict masked tokens. It provides a principled generative approach for probabilistic inference by optimizing a likelihood lower bound. Across extensive benchmarks on general tasks, math, code, and so on, LLaDA demonstrates strong scalability and performs comparably to our self-constructed ARM baselines. Remarkably, LLaDA 8B is competitive with strong LLMs like LLaMA3 8B in in-context learning and, after SFT, exhibits impressive instruction-following abilities in case studies such as multi-turn dialogue. Moreover, LLaDA addresses the reversal curse, surpassing GPT-4o in a reversal poem completion task. Our findings show the promise of diffusion models for language modeling at scale and challenge the common assumption that core LLM capabilities discussed above inherently depend on ARMs._"
    * https://doi.org/10.48550/arXiv.2502.09992
    * https://ml-gsai.github.io/LLaDA-demo/
      * https://huggingface.co/GSAI-ML
      * https://github.com/ML-GSAI/LLaDA
        * "_Official PyTorch implementation for 'Large Language Diffusion Models'_"


- Mercury: Ultra-Fast Language Models Based on Diffusion
  + https://arxiv.org/abs/2506.17298
    * "_We present Mercury, a new generation of commercial-scale large language models (LLMs) based on diffusion. These models are parameterized via the Transformer architecture and trained to predict multiple tokens in parallel. In this report, we detail Mercury Coder, our first set of diffusion LLMs designed for coding applications. Currently, Mercury Coder comes in two sizes: Mini and Small. These models set a new state-of-the-art on the speed-quality frontier. Based on independent evaluations conducted by Artificial Analysis, Mercury Coder Mini and Mercury Coder Small achieve state-of-the-art throughputs of 1109 tokens/sec and 737 tokens/sec, respectively, on NVIDIA H100 GPUs and outperform speed-optimized frontier models by up to 10x on average while maintaining comparable quality. We discuss additional results on a variety of code benchmarks spanning multiple languages and use-cases as well as real-world validation by developers on Copilot Arena, where the model currently ranks second on quality and is the fastest model overall._"


- CDLM: Consistency Diffusion Language Models For Faster Sampling
  + https://arxiv.org/abs/2511.19269
    * "_Diffusion Language Models (DLMs) offer a promising parallel generation paradigm but suffer from slow inference due to numerous refinement steps and the inability to use standard KV caching. We introduce CDLM (Consistency Diffusion Language Models), a training-based acceleration method that simultaneously tackles both bottlenecks. CDLM integrates consistency modeling to drastically reduce the number of required sampling steps by enabling multi-token finalization. Furthermore, we enforce a block-wise causal attention mask during fine-tuning, making the model fully compatible with KV caching. Experiments show CDLM achieves 3.6x-14.5x lower latency while maintaining competitive accuracy on math and coding tasks._"

    
