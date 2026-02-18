---
title: "Parameter-Efficient Fine-Tuning with InstructLab"
subtitle: ""
date: 2026-02-15
author: "Henry Xiao"
tags:
  - AI
  - Data
  - IBM
  - Enterprise AI
  - watsonx
---

Back in 2024, my team and I fine-tuned a Lllama model leveraging InstrutLab and Large-scale Alignment for Chatbot (LAB) method: generating synthetic data with a teacher model, and performing Parameter-Efficient-Fine-Tuning (PEFT) to inject IBM Risk Atlas domain expertise into the opensource generative AI model. 

Upon the public archival of the InstructLab project and the subsequent migrations to the individual component projects: [Synthetic Data Generation Hub](https://github.com/Red-Hat-AI-Innovation-Team/sdg_hub) and [Training Hub](https://github.com/Red-Hat-AI-Innovation-Team/training_hub) (an interface for common AI training including Supervised Fine-tuning, Continual Learning, LoRA, ...), I am reflecting on my experience with PEFT and some other thoughts with model tuning. 

## Why are we fine-tuning a model? 
What does it mean to fine tune a model? Fine-tuning models involves adapting pre-trained AI to specific tasks or domains, ranging from full parameter updates to efficient, resource-saving methods. Foundational models have been trained on a large, diverse dataset and are suitable for a wide range of general tasks such as text generation, information retrieval, image generation, codes, and others. 

Fine-tuning a foundational model aims to improve a model's performance on a specific task, within a particular domain, improve its output characteristics, or adapt to new data - all without the full re-training of the model. 

## Fine-Tuning Techniques 

[Parameter-Efficient Fine-Tuning](https://www.ibm.com/think/topics/parameter-efficient-fine-tuning) 

---
Work in progress... stay tuned 