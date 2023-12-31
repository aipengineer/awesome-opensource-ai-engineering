# LLaMA.cpp
![The AI Engineer presents LLaMA.cpp](llama.cpp_1920x192.png)
## Overview
LLaMA.cpp runs LLaMA and other large language models fast and small using integer quantization, supports AVX and GPU acceleration, works across Linux/Mac/Windows, and has Python/Node/Rust bindings - an optimal open source library for deploying performant LLM inference.

## Description
Deploying giant language models like GPT-3 in production is hard. You need low latency, a small memory footprint, and portability across devices and OSes. That's where LLaMA.cpp comes in. 🦙

👉 Blazing Fast Inference
LLaMA.cpp uses techniques like 4-bit integer quantization, SIMD optimization with AVX/NEON, and GPU acceleration via CUDA, ROCm, and Metal to make LLM inference screaming fast.

⚡️How fast? We're talking that over 1400 tokens are generated per second on a MacBook Pro! It easily keeps up with real-time chat and text generation applications.

Storing the full high-precision weights of language models takes massive amounts of RAM and disk space. Llama.cpp has you covered by compressing these down to just 3-5 bits per weight - a 4-5x reduction! - using novel lossless and lossy quantization techniques with minimal quality impact.

It allows you to effectively "compress" models 3-4x and make much larger models fit into limited memory and disk budgets during inference.

🛰️ Cross Platform Portability

Getting models deployed across the dizzying variety of environments required by different products is challenging.

Thankfully, LLaMA.cpp provides native high-performance support for Linux, MacOS, and Windows on x86 & ARM CPUs and Android and iOS with custom backends leveraging GPUs via CUDA, ROCm, OpenCL, and Metal.

This flexible architecture makes performant deployment straightforward across platforms and devices, from cloud VMs to mobiles and browsers.

🔌 Integrates Into Your Stack

LLaMA.cpp empowers you to integrate performant LLM prediction into your existing infrastructure easily, no matter the language or environment.

With bindings for Python, Node.js, Rust, C#, Java, Clojure, and integration with runtimes like OpenAI, llama.cpp slots cleanly into your favorite workflow.

The modular, dependency-free architecture even allows the use of llama.cpp on exotic platforms like Arduino and ESP32!

### 💡 LLaMA.cpp Key Highlights
🛠 Custom integer quantization to enable efficient low-precision matrix multiplication, reducing memory bandwidth while retaining accuracy

💻 Aggressive multi-threading and batch processing for massively parallel token generation across CPU cores

🧱 Runtime code generation for critical functions like softmax to optimize for the specific instruction set

✨Architecture specific tuning for x86, ARM, and GPUs to extract every ounce of performance

🧠 Extreme Memory Savings


### 🤔 Why should The AI Engineer care about LLaMA.cpp?

1. 👉 It's fast - LLaMA.cpp leverages techniques like 4-bit integer quantization, SIMD vectorization with AVX/NEON, and GPU acceleration via CUDA, ROCm, and Metal to achieve high inference performance. It enables you to deploy responsive large language model applications. Specific optimizations include:

- Custom integer quantization schemes that allow efficient low-precision matrix multiplication
- Multi-threading and batch processing for parallel token generation
- Runtime code generation for critical functions like softmax
- Architecture specific tuning for x86, ARM, and GPUs

2. 🧠 It's small - LLaMA.cpp implements novel lossless and lossy quantization techniques that compress full-precision transformer weights down to as little as 3-5 bits per weight with minimal quality loss. It allows you to effectively "compress" models 3-4x and fit larger models than possible into limited memory budgets for inference.

3. ⚙️ It's portable - With native Linux, MacOS, Windows, Android, iOS, and WebAssembly support across x86, ARM, and GPU architectures, llama.cpp makes performant deployment easy across platforms and devices, from servers to mobiles and browsers. This flexibility is enabled by its modular, dependency-free architecture.

4. 🌎 It's flexible - Thanks to language bindings for Python, Node.js, Rust, C#, Java, and more, and integration with inference APIs like OpenAI, llama.cpp makes integrating performant LLM inference into your existing infrastructure simple. You can keep your favorite workflow.

5. 🔌 It's open - As an MIT licensed open source project with a welcoming, rapidly growing international community and over 100 contributors, llama.cpp empowers the community to improve LM inference continuously. Anyone can inspect the code, fix bugs, add features, tune for their use case, and more.

## 📊 Tell me more about LLaMA.cpp!
* 👷🏽‍♀️ Builders: Georgi Gerganov, slaren, Jared Van Bortel, Johannes Gäßler
* 👩🏽‍💼 Builders on LinkedIn: https://www.linkedin.com/in/georgi-gerganov-b230ab24/, https://www.linkedin.com/in/jaredvanbortel/
* 👩🏽‍🏭 Builders on X: https://twitter.com/ggerganov
* 👩🏽‍💻 Contributors: 481
* 💫 GitHub Stars: 47.8k
* 🍴 Forks: 6.8k
* 👁️ Watch: 466
* 🪪 License: MIT
* 🔗 Links: Below 👇🏽

## 🖇️ Where can I find out more about LLaMA.cpp?
* GitHub Repository: https://github.com/ggerganov/llama.cpp
* Profile in The AI Engineer: https://github.com/theaiengineer/awesome-opensource-ai-engineering/blob/main/libraries/llama.cpp/README.md

---
🧙🏽 Follow [The AI Engineer](https://www.linkedin.com/company/theaiengineer/) for more about llama.cpp and daily insights tailored to AI engineers. Subscribe to our [newsletter](http://theaiengineerco.substack.com). We are the AI community for hackers!

♻️ Repost this to help LLaMA.cpp become more popular. Support AI Open-Source Libraries!

⚠️ If you want me to highlight your favorite AI library, open-source or not, please share it in the comments section!