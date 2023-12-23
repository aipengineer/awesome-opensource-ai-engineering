# vLLM
![The AI Engineer presents vLLM](vllm_1920x192.png)
## Overview
vLLM enables fast large language model inference and serving through innovations like PagedAttention for efficient memory management.

## Description

AI engineers want to build services leveraging the latest capabilities of models like GPT and PaLM. But hosting and serving these giant neural networks introduces bottlenecks that constrain throughput and increase latency.

That's why researchers at UC Berkeley built vLLM - an open-source library for serving language models.

It tackles the memory bottleneck by:

✅ Introducing PagedAttention to store attention keys/values in GPU memory efficiently. It cuts fragmentation from 80% to under 4%!

✅ Enabling memory sharing across concurrent requests through the page table mapping.

### 💡 vLLM Key Highlights
1. Efficient Inference and Serving: vLLM introduces PagedAttention, a memory-optimized attention algorithm that improves GPU memory usage, resulting in up to 24x higher throughput than HuggingFace Transformers. 

2. User-Friendly Integration and Accessibility: vLLM integrates with popular HuggingFace models, such as GPT-3, PaLM, and LLaMA, making it a convenient drop-in replacement for applications using OpenAI. 


### 🤔 Why should The AI Engineer care about vLLM?
1. 🚀 It enables building high-throughput LLM-based services by optimizing GPU memory allocation and request batching. Critical for real-world applications.
2. 📈 It achieves substantially higher serving performance through PagedAttention, setting new benchmarks. Keep response times low.
3. ⚙️ It natively supports distributing large models across GPUs and quantization to optimize size. Make giant models usable.
4. 🔌 It integrates seamlessly with popular HuggingFace libraries for easy adoption. Reuse existing workflow.
5. 👩‍💻 It provides an easy-to-use interface and OpenAI API server for quickly building from prototypes to production systems. Accelerate development.

## 📊 Tell me more about vLLM!
* 👷🏽‍♀️ Builders: Woosuk Kwon, Zhuohan Li
* 👩🏽‍💼 Builders on LinkedIn: https://www.linkedin.com/in/woosuk-kwon-986551262/, https://www.linkedin.com/in/zhuohan-li/
* 👩🏽‍🏭 Builders on X: https://twitter.com/woosuk_k, https://twitter.com/zhuohan123
* 💾 Used in 246 repositories
* 👩🏽‍💻 Contributors: 155
* 💫 GitHub Stars: 12.1k
* 🍴 Forks: 1.4k
* 👁️ Watch: 128
* 🪪 License: Apache-2.0
* 🔗 Links: Below 👇🏽

## 🖇️ Where can I find out more about vLLM?
* GitHub Repository: https://github.com/vllm-project/vllm
* Official Website: https://docs.vllm.ai
* Discord Server: https://discord.com/invite/jz7wjKhh6g
* Profile in The AI Engineer: https://github.com/theaiengineer/awesome-opensource-ai-engineering/blob/main/libraries/vllm/README.md

---
🧙🏽 Follow [The AI Engineer](https://www.linkedin.com/company/theaiengineer/) for more about vLLM and daily insights tailored to AI engineers. Subscribe to our [newsletter](http://theaiengineerco.substack.com). We are the AI community for hackers!

♻️ Repost this to help vLLM become more popular. Support AI Open-Source Libraries!

⚠️ If you want me to highlight your favorite AI library, open-source or not, please share it in the comments section!