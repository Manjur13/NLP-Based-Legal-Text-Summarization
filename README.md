<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f3815835-36c9-49b3-b209-fa5afe34d2cf" />

# 🧾 Legal Document Summarizer

> A multi-model system for summarizing complex legal documents using deep learning and Transformer models.  
> Built with TensorFlow, Keras, and Hugging Face Transformers — featuring both custom Seq2Seq (LSTM/GRU) and pre-trained models (T5, PEGASUS).

[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Dataset](https://img.shields.io/badge/Dataset-BillSum-blueviolet)](https://huggingface.co/datasets/FiscalNote/billsum)
[![Model Hub](https://img.shields.io/badge/models-HuggingFace-purple)](https://huggingface.co/models)
[![Framework](https://img.shields.io/badge/framework-TensorFlow-orange)](https://www.tensorflow.org/)
[![App](https://img.shields.io/badge/Streamlit-Demo-red)](#streamlit-app-demo)

---

## 🧠 Overview

This project implements **Legal Document Summarization** using both **classical Seq2Seq (LSTM/GRU)** models and **Transformer-based models (T5, PEGASUS)**.  
It is trained on the **BillSum dataset**, which contains U.S. Congressional and California State bills.

The summarizer extracts concise, meaningful summaries from lengthy legal documents — making them easier to read, interpret, and analyze.

⚠️ **Disclaimer:** This is a research and educational project — not intended as legal advice.

---

## ✨ Key Features

- 📚 **Dataset:** [BillSum (FiscalNote)](https://huggingface.co/datasets/FiscalNote/billsum) – legal bill summaries dataset.
- 🧹 **Text Preprocessing:** Lemmatization, stemming, stopword removal, and text normalization.
- 🧠 **Models Implemented:**
  - Custom **Seq2Seq (LSTM/GRU)** with attention.
  - Transformer-based **T5** and **PEGASUS** models.
  - Extractive **BERT** baseline for comparison.
- 📊 **Evaluation Metrics:** ROUGE-1, ROUGE-2, ROUGE-L, accuracy, and loss plots.
- 📄 **Visualization:** WordClouds, token frequency charts, and summary comparison plots.
- 🧩 **Streamlit Interface:** Real-time document upload and summarization via a simple web UI.
- 🧪 **Evaluation Suite:** ROUGE & BERTScore, factuality heuristics, and readability analysis.
- ⚙️ **Configurable Pipeline:** Change models, hyperparameters, and token lengths easily in one place.

---

## 🧰 Tech Stack

| Component | Library / Framework |
|------------|---------------------|
| Language | Python 3.10+ |
| Deep Learning | TensorFlow, Keras |
| Transformers | Hugging Face Transformers |
| NLP Tools | NLTK, SpaCy, TextBlob |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Web App | Streamlit |
| Dataset | BillSum (FiscalNote) |

---

## 🧩 Project Workflow

```text
📥 Load Dataset (BillSum)
   ↓
🧹 Preprocess Text (Tokenization, Lemmatization)
   ↓
🧠 Train Models (Seq2Seq, T5, PEGASUS)
   ↓
🧾 Generate Summaries
   ↓
📈 Evaluate using ROUGE Scores
   ↓
🌐 Deploy Streamlit App for Live Demo
