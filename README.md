# Crosscoders: Open Source Replication for Model Diffing

This project is an **open-source replication** of [Anthropic's Crosscoders](https://transformer-circuits.pub/2024/crosscoders/index.html#model-diffing), specifically focusing on their **model diffing** methodology.

Crosscoders are small Transformer-based networks trained to predict and translate between different residual streams within or across models. This implementation replicates the training and evaluation of a Crosscoder trained to model-diff the **Qwen Base Models** models at a **middle residual stream layer**.

## 🧠 Objective

The goal is to replicate and understand how Crosscoders can learn the difference between models' internal representations—what Anthropic calls "model diffing." This can shed light on how model fine-tuning affects internal representations at various layers.

## 📄 Reference

- [Crosscoders: Transformer Circuits Thread](https://transformer-circuits.pub/2024/crosscoders/index.html#model-diffing)

## 🛠️ Features

- Implements training of a Crosscoder to learn differences between two model residual streams.
- Uses intermediate residual activations from the **Qwen Base** models.
- Focuses on the **middle layer** of the Transformer for training and evaluation.



