<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f3815835-36c9-49b3-b209-fa5afe34d2cf" /># 🧾 Legal Document Summarizer

> Multi-model legal summarization with Transformer encoder-decoders (T5, PEGASUS, LED/Long T5), Seq2Seq, extractive BERT, and optional GPT inference.


[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Tests](https://img.shields.io/badge/tests-passing-brightgreen.svg)](#testing)
[![Model Hub](https://img.shields.io/badge/models-HF%20Transformers-purple)](https://huggingface.co/models)
[![Gradio Demo](https://img.shields.io/badge/demo-Gradio-orange)](#quick-demo-optional)

A legal document summarizer leveraging multiple NLP models including Transformer-based encoder-decoders, Seq2Seq, BERT, GPT, T5, and PEGASUS.  
Designed to extract concise and relevant summaries from complex legal documents for improved understanding and analysis.

⚠️ **Disclaimer:** This software is a research/education tool and **not** legal advice.

---

## ✨ Key Features
- 🔀 **Multi-model ensemble** — abstractive (T5/PEGASUS/Long-T5/LED), extractive (BERT w/ sentence scoring), and optional GPT for refinement.
- 🧱 **Modular pipeline** — `ingest → preprocess → train → infer → evaluate`.
- 📄 **PDF-first** — built-in PDF parsing, OCR fallback, and chunking for long docs.
- 🧪 **Evaluation suite** — ROUGE-1/2/L, BERTScore, length control, factuality checks (heuristic).
- ⚙️ **Config-driven** — YAML configs to switch models, hyperparams, and thresholds.
- 🐳 **Reproducible** — Dockerfile + Makefile for consistent runs.
- 🎛️ **CLI & API** — simple commands + Python API for integration.

---
