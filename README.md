# LORYX
# LORYX: Parameter-Efficient Fine-Tuning of LLMs for News Summarization

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/release/python-3100/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O1cucAeVerWq2iht6ndMQK1h_Vq2wPJ0)

**LORYX** (LoRA-based sYstem for News Summarization) is a parameter-efficient news summarization system that trains only **0.79% of parameters** while achieving high-quality abstractive summaries.

## ✨ Features

- **Parameter Efficient**: Trains only 1.77M parameters (0.79%) instead of 224M
- **High Quality**: +26.4% ROUGE-1, +47.7% ROUGE-2 improvements over baseline
- **Resource Friendly**: Runs on free-tier Google Colab (T4 GPU)
- **Fast Training**: 78.6% faster than full fine-tuning (45 min vs 3.5 hours)
- **Deployable**: Streamlit web app hosted on Hugging Face Spaces

## 🎮 Live Demo

- **Google Colab Notebook**: [Open in Colab](https://colab.research.google.com/drive/1O1cucAeVerWq2iht6ndMQK1h_Vq2wPJ0)
- **Web App**: [Hugging Face Spaces](https://huggingface.co/spaces/your-username/loryx) *(add your link)*

## 📊 Results

| Metric | Baseline | LORYX | Improvement |
|--------|----------|-------|-------------|
| ROUGE-1 | 0.2837 | **0.3585** | +26.4% |
| ROUGE-2 | 0.1108 | **0.1637** | +47.7% |
| ROUGE-L | 0.2138 | **0.2681** | +25.5% |

**Efficiency Gains:**
- Parameter reduction: **99.21%**
- Training time: **78.6% faster**
- GPU memory: **48.6% less**

## 🚀 Quick Start

1. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1O1cucAeVerWq2iht6ndMQK1h_Vq2wPJ0)
2. Click "Runtime" → "Run all"
3. The notebook will install dependencies, download data, and train the model

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/LORYX.git
cd LORYX

# Install dependencies
pip install -r requirements.txt
