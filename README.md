# Aggressive and Offensive Language Detection for Cyber Trolling using NLP

## 📌 Overview

This repository contains the implementation and experimental analysis for the research work titled:

**“Aggressive and Offensive Language Detection for Identifying Cyber Trolling from Social-Media Text using NLP”**

The project presents a comprehensive study of **Machine Learning**, **Deep Learning**, and **Transformer-based** approaches for detecting aggressive and offensive language in social media text. Experiments are conducted on two benchmark datasets: **OLID** and **Cyber-Troll**.

This work is part of the **Master of Engineering (Software Engineering)** thesis at **Jadavpur University**.

---

## 🎯 Research Contributions

- Comparative evaluation of:
  - Traditional Machine Learning models (SVM, Logistic Regression, Naïve Bayes)
  - Deep Learning models (CNN, LSTM, BiLSTM)
  - Transformer-based models (BERT, RoBERTa, XLM-RoBERTa)
- Use of multiple feature representations:
  - TF-IDF, Bag-of-Words
  - Word2Vec, GloVe, FastText embeddings
  - NRC Emotion Lexicon features
- Proposal of a **novel hybrid feature fusion framework**:
  - GloVe embeddings combined with **SVM decision scores**
  - Integrated into CNN, LSTM, and BiLSTM architectures
- Extensive experimental evaluation using:
  - Accuracy
  - Precision
  - Recall
  - Macro F1-score
- Achieved **state-of-the-art performance**:
  - **98.1% Accuracy on OLID**
  - **98.35% Accuracy on Cyber-Troll**

---

## 🧠 Methodology

The research explores three major experimental pipelines:

### 🔹 Approach 1: Traditional ML & Multi-Feature Deep Learning
- **ML Models**: SVM, Logistic Regression, Naïve Bayes  
- **Features**: TF-IDF, Bag-of-Words  
- **DL Models**: CNN, LSTM, BiLSTM  
- **Embeddings**: Word2Vec, GloVe, FastText, NRC Emotion Features  

### 🔹 Approach 2: Transformer-Based Fine-Tuning
- BERT
- RoBERTa
- XLM-RoBERTa  
- Tokenization using HuggingFace Transformers with padding, truncation, and attention masks  

### 🔹 Approach 3: Proposed Hybrid Fusion Model (Novel Contribution)
- GloVe word embeddings
- SVM decision scores as auxiliary features
- Deep Learning classifiers:
  - CNN
  - LSTM
  - BiLSTM

---

## 📊 Datasets

| Dataset | Description |
|-------|-------------|
| **OLID** | Offensive Language Identification Dataset (SemEval-2019) |
| **Cyber-Troll** | English dataset for cyber-aggression and trolling detection |

> ⚠️ Datasets are publicly available and are **not redistributed** in this repository.

---

## 📂 Repository Structure


---

## 🧪 Experimental Results

- Hybrid fusion models consistently outperform standalone models
- Transformer-based models provide strong contextual baselines
- Combining **symbolic decision boundaries (SVM)** with **deep semantic embeddings** yields the best performance

Recommended evaluation artifacts:
- Confusion matrices
- Accuracy and F1-score comparison plots
- Model architecture diagrams

---

## 🚀 How to Run

### Install dependencies
'''bash
pip install -r requirements.txt


2. Execute notebooks in the following order:

ML_Cyber_Troll_OLID.ipynb

OLID_aggression.ipynb

CYBER-TROLL_aggression.ipynb

novel_OLID_CyberTroll.ipynb
