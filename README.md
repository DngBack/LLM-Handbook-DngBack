# LLM-Notes 🚀

A comprehensive collection of notes, insights, and experiments on Large Language Models (LLMs). This repository serves as a knowledge hub for everything related to LLMs, from theoretical foundations to practical deployment, fine-tuning strategies, and experimental implementations.

## Table Of Contents

- [📌 Introduction to LLMs](#introduction-to-llms): Basics, architectures, mathematical foundations, and key concepts.
- [🛠 LLM PostTraining](#llm-fine-tuning): Techniques, frameworks, and best practices.
- [🎮 Deployment Strategies](#deployment-strategies): Serving LLMs using ONNX, FastAPI, Triton, and other tools.
- [💪 Optimization & Scaling](#optimization--scaling): Quantization, pruning, and performance tuning.
- [🌐 Real-world Applications](#real-world-applications): Scripts and test cases to evaluate different models and settings.

## 🚀 Why This Repo?

- Deeply explores the theory and mathematics behind LLMs.
- Provides practical test repositories to evaluate models.
- Offers a hands-on approach with experiments and deployment guides.
- Serves as a resource hub for engineers, researchers, and enthusiasts.

## 📌 Introduction to LLMs

- Basics, architectures, mathematical foundations, and key concepts.

| Title   | Description                                                                                                                                                                           | Link                                                             | Notes                               |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------- |
| Gemma 3 | ​Gemma 3 is Google's latest open-source AI model, optimized to run efficiently on a single GPU or TPU. It supports over 140 languages and can process text, images, and short videos. | [Link](https://developers.googleblog.com/en/introducing-gemma3/) | [Gemma3](./FoudationModels/Gemma3/) |

## 📊 Mathematical Understanding

- Attention mechanisms, transformers, loss functions, optimization techniques.

## 🛠️ LLM PostTraining

- Techniques, frameworks, and best practices.

| Title                 | Description                                                                                                                                                                                    | Link                                                        | Notes |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ----- |
| **Unsloth**           | A lightweight library designed for rapid and memory-efficient fine-tuning of LLMs, fully compatible with the Hugging Face ecosystem. :contentReference                                         | [GitHub](https://github.com/unslothai/unsloth)              |       |
| **PEFT**              | Provides state-of-the-art parameter-efficient fine-tuning techniques, enabling adaptation of pre-trained models to specific tasks without extensive computational resources. :contentReference | [GitHub](https://github.com/huggingface/peft)               |       |
| **TRL**               | Offers tools to train transformer language models using reinforcement learning, facilitating the alignment of models with human preferences. :contentReference                                 | [GitHub](https://github.com/huggingface/trl)                |       |
| **Axolotl**           | Streamlines post-training processes for various AI models, incorporating community-maintained best practices for efficient fine-tuning. :contentReference                                      | [GitHub](https://github.com/axolotl-ai-cloud/axolotl/)      |       |
| **LLMBox**            | Provides a unified training pipeline and comprehensive model evaluation for implementing LLMs, enhancing the efficiency of training and deployment.                                            | [GitHub](https://github.com/RUCAIBox/LLMBox)                |       |
| **LitGPT**            | Facilitates lightning-fast training and fine-tuning of LLMs, leveraging the capabilities of the Lightning-AI platform.                                                                         | [GitHub](https://github.com/Lightning-AI/litgpt)            |       |
| **Mergoo**            | Enables the merging of multiple LLM experts and efficient training of the merged models, promoting collaborative model development.                                                            | [GitHub](https://github.com/Leeroo-AI/mergoo)               |       |
| **Llama-Factory**     | Offers easy and efficient fine-tuning of LLMs, supporting various model architectures and facilitating rapid deployment.                                                                       | [GitHub](https://github.com/hiyouga/LLaMA-Factory)          |       |
| **Ludwig**            | A low-code framework for building custom LLMs, neural networks, and other AI models, simplifying the model development process.                                                                | [GitHub](https://github.com/ludwig-ai/ludwig)               |       |
| **Txtinstruct**       | Provides a framework for training instruction-tuned models, enhancing the ability of LLMs to follow specific directives.                                                                       | [GitHub](https://github.com/neuml/txtinstruct)              |       |
| **Lamini**            | An integrated platform for LLM inference and tuning, offering tools for efficient model deployment and customization.                                                                          | [GitHub](https://github.com/lamini-ai/lamini)               |       |
| **xTuring**           | Enables fast, efficient, and simple fine-tuning of open-source LLMs, such as Mistral, LLaMA, GPT-J, and more.                                                                                  | [GitHub](https://github.com/stochasticai/xTuring)           |       |
| **RL4LMs**            | A modular reinforcement learning library designed to fine-tune language models to align with human preferences and specific tasks.                                                             | [GitHub](https://github.com/allenai/RL4LMs)                 |       |
| **DeepSpeed**         | A deep learning optimization library that simplifies distributed training and inference, making them more efficient and effective.                                                             | [GitHub](https://github.com/microsoft/DeepSpeed)            |       |
| **torchtune**         | A PyTorch-native library specifically designed for fine-tuning LLMs, offering a lean, extensible, and abstraction-free design.                                                                 | [GitHub](https://github.com/pytorch/torchtune)              |       |
| **PyTorch Lightning** | Provides a high-level interface for pretraining and fine-tuning LLMs, streamlining the training process and improving scalability.                                                             | [GitHub](https://github.com/Lightning-AI/pytorch-lightning) |       |

## 🎮 Deployment Strategies

- Serving LLMs using ONNX, FastAPI, Triton, and other tools.

## 💪 Optimization & Scaling

- Quantization, pruning, and performance tuning.

## 🌐 Real-world Applications

- Case studies, automation, and integration examples.

## 🎧 LLM Test Repository

- Scripts and test cases to evaluate different models and settings.
