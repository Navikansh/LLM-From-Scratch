# LLM From Scratch

This repository contains my implementation of core components of a
Transformer-based language model built from scratch in PyTorch.

The goal of this project is to understand how modern large language
models work internally by implementing their building blocks.

## Implemented Components

- Text preprocessing and tokenization
- Word embeddings
- Scaled dot-product attention
- Multi-head attention
- Transformer blocks
- Language model training

## Architecture

Input Text
↓
Tokenization
↓
Embedding Layer
↓
Multi-head Attention
↓
Transformer Blocks
↓
Output Language Model

## Experiments

The model was trained on a small text corpus to analyze:

- attention patterns
- training loss behavior
- token prediction accuracy
