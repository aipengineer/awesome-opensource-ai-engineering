# Whisper
![The AI Engineer presents Whisper](whisper_1920x192.png)
## Overview
Whisper is an open-sourced speech recognition system from OpenAI. It uses a seq2seq model trained on 680k hours of diverse audio to enable robust transcription and translation across languages and contexts. 

## Description

Whisper 🤫 is an automatic speech recognition (ASR) system released by OpenAI in September 2022. It builds on the Transformer architecture using an encoder-decoder model trained on a massive dataset of 680,000 hours of multilingual speech audio scraped from the internet.

What sets Whisper apart is the scale and diversity of its training data. Rather than relying on curated speech datasets, it learns from "found data" on the web, including audio with background noise, accents, and technical jargon. 👂 This leads to improved out-of-the-box robustness compared to other ASR models - Whisper reaches near state-of-the-art results without any fine-tuning on downstream tasks.

The model is trained in a multitasking fashion to handle transcription, translation (68 languages), voice activity detection and more. At inference time, these tasks are specified to the decoder via a simple text prompt interface. Despite the model's size (1.5B parameters), inference is fast and memory-efficient thanks to optimizations like mixed precision and activation checkpointing.

In analyses, Whisper matches professional human transcribers in Word Error Rate while exceeding other ASR systems in noisy conditions. The researchers share not just inference code and hosted models, but also tools to reproduce the weakly supervised training pipeline. This makes Whisper a promising foundation for real-world speech applications as well as further research.

The project shows the potential for internet-scale weakly supervised learning. What other tasks could benefit from pre-training on massive found data? Let me know your ideas in the comments! 💬

### 💡 Whisper Key Highlights
📥 Easy to use - load models and transcribe audio in just a few lines of Python

⚡️ Fast inference - optimized for speed and memory efficiency

🛠️ Customizable - supports beam search, temperature scheduling, and other decoding options

### 🤔 Why should The AI Engineer care about whisper?

1. 👂 Robust performance across accents, backgrounds and languages - Whisper is trained on an unprecedented 680,000 hours of diverse multi-language speech data. This allows it to handle challenging real-world speech much better - whether different accents, background noise or technical vocabulary. It even translates speech to English from 98 languages it wasn't specifically trained on through zero-shot learning. This level of robustness opens many new use cases.

2. 🔬 Excellent foundation for advancing speech AI research - Whisper uses a simple Transformer seq2seq architecture, yet achieves state-of-the-art levels of accuracy without specialization to particular datasets. This makes it an ideal base model to study generalization, capabilities, biases and other properties of speech AI systems. Researchers can also advance the field by building on Whisper's innovations.

3. ✂️ Modular pipeline replacement in one model - Whisper encapsulates transcription, translation, language identification etc within a single model by using special tokens to switch tasks. This replaces the traditional complex pipeline of specialized models. The simplicity enables faster innovation.

4. 💡 Inspiration for speech interface innovation - By providing high accuracy together with ease of use, Whisper lowers barriers for developers exploring ideas that use speech interfaces. Its robustness also opens possibilities like real-time dictation, translation apps, voice tools for people with disabilities etc.

5. 🆓 Fully open sourced - The Whisper code, models and detailed model cards are provided open source without restrictions. This allows responsible research and development by the wider AI community to advance speech recognition for social good. Ongoing feedback will improve it.

## 📊 Tell me more about Whisper!
* 👷🏽‍♀️ Builders: Jong Wook Kim
* 👩🏽‍💼 Builders on LinkedIn: https://www.linkedin.com/in/jongwook-kim/
* 👩🏽‍🏭 Builders on X: https://twitter.com/_jongwook_kim
* 👩🏽‍💻 Contributors: 68
* 💫 GitHub Stars: 53.7k
* 🍴 Forks: 6.1k
* 👁️ Watch: 461
* 🪪 License: MIT
* 🔗 Links: Below 👇🏽

## 🖇️ Where can I find out more about Whisper?
* GitHub Repository: https://github.com/openai/whisper
* Official Website: https://openai.com/research/whisper
* Profile in The AI Engineer: https://github.com/theaiengineer/awesome-opensource-ai-engineering/blob/main/libraries/whisper/README.md

---
🧙🏽 Follow [The AI Engineer](https://www.linkedin.com/company/theaiengineer/) for more about whisper and daily insights tailored to AI engineers. Subscribe to our [newsletter](http://theaiengineerco.substack.com). We are the AI community for hackers!

♻️ Repost this to help whisper become more popular. Support AI Open-Source Libraries!

⚠️ If you want me to highlight your favorite AI library, open-source or not, please share it in the comments section!