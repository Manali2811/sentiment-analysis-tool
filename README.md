# 🎭 Sentiment Analysis Tool

> Detect emotions in text using state-of-the-art NLP — powered by HuggingFace Transformers

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![HuggingFace](https://img.shields.io/badge/🤗-HuggingFace-yellow.svg)](https://huggingface.co)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview

This project implements a **Sentiment Analysis pipeline** using a pre-trained DistilBERT model fine-tuned on the Stanford Sentiment Treebank (SST-2). Given any text, the model predicts whether the sentiment is **POSITIVE** or **NEGATIVE** — along with a confidence score.

### ✨ Features
- 🔍 Single and batch text sentiment prediction
- 📊 Confidence score visualization
- 📦 Real-world product review analysis
- 💬 Interactive input mode
- 📈 Charts and summary reports

---

## 🖼️ Sample Output

```
📝 Text     : I absolutely loved this product!
😊 Sentiment : POSITIVE
🎯 Confidence: 99.87%
```

---

## 🧠 Model

| Property | Value |
|---|---|
| Model | `distilbert-base-uncased-finetuned-sst-2-english` |
| Source | HuggingFace Model Hub |
| Task | Binary Sentiment Classification |
| Size | ~250MB |
| Speed | ~60% faster than BERT, 97% of performance |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/sentiment-analysis-tool.git
cd sentiment-analysis-tool
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter
```bash
jupyter notebook sentiment_analysis.ipynb
```

---

## 📦 Requirements

```
transformers>=4.30.0
torch>=2.0.0
pandas>=1.5.0
matplotlib>=3.6.0
seaborn>=0.12.0
notebook>=6.5.0
```

---

## 📁 Project Structure

```
sentiment-analysis-tool/
│
├── sentiment_analysis.ipynb   # Main notebook
├── requirements.txt           # Dependencies
├── README.md                  # You're here!
└── .gitignore                 # Git ignore file
```

---

## 🔬 Notebook Sections

| # | Section | Description |
|---|---|---|
| 1 | Setup | Install libraries and configure environment |
| 2 | Load Model | Pull pre-trained DistilBERT from HuggingFace |
| 3 | Single Prediction | Analyze individual text inputs |
| 4 | Batch Analysis | Process multiple texts with DataFrame output |
| 5 | Visualization | Pie charts and confidence bar charts |
| 6 | Product Reviews | Real-world simulation with star rating comparison |
| 7 | Interactive Mode | Type any text and get instant predictions |

---

## 🚀 Extensions & Ideas

- 🌍 Swap to a multilingual model (`xlm-roberta`) for other languages
- 🎯 Add aspect-based sentiment (fine-grained opinion mining)
- 🌐 Wrap in a **Streamlit** or **Gradio** web app
- 🔧 Fine-tune on your own dataset using HuggingFace Trainer

---

## 📄 License

MIT License — feel free to use and modify!

---

*Made with 🤗 HuggingFace · Python · Pandas · Matplotlib*
