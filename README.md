# Transformer Architecture

Decoder-only transformer internals — from a visual walkthrough to RTL and from PyTorch to quantisation.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Transformer_Architecture/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Transformer Decoder — Visual Deep Dive](https://github.com/BrendanJamesLynskey/LLM_Transformer_Decoder_guide) | live | Interactive visual walkthrough of every operation inside a decoder-only transformer, from tokenisation to generation. |
| 02 | [Transformer Decoder — Every Computation](https://github.com/BrendanJamesLynskey/Transformer_Decoder_walkthrough) | live | Browser-based forward pass with real tensor values — GQA, RoPE, SwiGLU, RMSNorm, all from scratch in vanilla JS. |
| 03 | [Transformer Decoder — RTL Accelerator](https://github.com/BrendanJamesLynskey/LLM_Transformer_Decoder_RTL) | live | Synthesisable SystemVerilog implementation of a pre-norm decoder block with KV-cache, plus an 83-test verification suite. |
| 04 | [Karpathy's nanoGPT — Step by Step](https://github.com/BrendanJamesLynskey/nanoGPT_presentation) | live | Interactive presentation walking through every line of Karpathy's ~200-line GPT — tokenisation, self-attention, blocks, training, generation. |
| 05 | [Transformer Decoder from Scratch](https://github.com/BrendanJamesLynskey/Python_Transformer_Decoder) | live | Step-by-step PyTorch implementation in a single Jupyter notebook — every component built from first principles and visualised. |
| 06 | [Neural Network Data Types](https://github.com/BrendanJamesLynskey/NN_data_types) | live | SystemVerilog implementations of 9 numerical formats (FP32 down to FP4) used in NN training and inference hardware. |
| 07 | [Hardware-Aware Quantisation](https://github.com/BrendanJamesLynskey/Hardware_Aware_Quantisation) | live | Interactive quantisation explorer — formats, weight distributions, schemes, simulated inference, hardware cost models, mixed-precision. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
