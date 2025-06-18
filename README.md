# DistilGPT2 Email Fine-Tuning

This project demonstrates how to fine-tune the DistilGPT2 model from Hugging Face Transformers to generate well-structured, grammatically correct emails (including subject lines) from text prompts.

The goal is to build a lightweight, fast, and domain-specific email assistant capable of drafting professional emails in different contexts.

## Key Features

- Uses Hugging Face Transformers and PyTorch
- Clean dataset preparation and formatting
- Custom email prompt-to-output generation
- Code modularized for reproducibility and future extensions

## Usage

Training is done via 🤗 `Trainer` with configurable arguments. The model is saved for inference and can be reloaded for real-time email generation.
