# Phishing Email Detection Using Deep Learning

## 📌 Overview

This project addresses the growing threat of social engineering attacks by developing high-accuracy deep learning models to detect phishing emails. While traditional machine learning methods struggle with evolving tactics and obscured language patterns, this research leverages **Natural Language Processing (NLP)** and **Neural Networks** to identify semantic context and stylistic anomalies.

**Authors:** Anthony Ward, Divya Kamila, William Brennan

## 🚀 Key Results

* **Best Model:** `charCNN-BERT`
* **F1-Score:** 0.994
* **Accuracy:** 99.0%
* **Dataset:** Evaluated on a standardized set of over **145,000 emails**.

## 🧠 Models Explored

The research assesses three distinct neural architectures within a common preprocessing and evaluation environment:

1. **charCNN-BERT:** Combines Character-level Convolutional Neural Networks with BERT embeddings to capture both structural and contextual information. (Highest Performance)
2. **LSTM-GRU Hybrid:** Utilizes gated units to capture long-term dependencies in email sequences. Noted for **high recall**, crucial for reducing false negatives in security.
3. **Hybrid BiLSTM-DNN:** A bidirectional approach to capture context from both ends of a sequence, coupled with a deep neural network for classification.

## 🛠️ Technical Implementation

* **Contextual Modeling:** Implementation of attention mechanisms to address semantic content.
* **Feature Engineering:** Detection of "stylistic anomalies" commonly found in social engineering.
* **Preprocessing:** Standardized pipeline for tokenization, cleaning, and sequence padding.
* **Evaluation:** Focus on F1-score and Recall to ensure real-world viability for cybersecurity solutions.

## 📊 Performance Comparison

| Model | Accuracy | F1-Score | Note |
| --- | --- | --- | --- |
| **charCNN-BERT** | **99.0%** | **0.994** | Best overall performance |
| **LSTM-GRU Hybrid** | High | High | Best for reducing False Negatives |
| **Hybrid BiLSTM-DNN** | Solid | Solid | Reliable baseline architecture |

## 📂 Project Structure

```text
├── data/               # Dataset references/links
├── models/             # Model architecture definitions
├── notebooks/          # Exploratory Data Analysis & Training scripts
├── preprocessing/      # Text cleaning and tokenization scripts
├── Paper_Final.pdf     # Full Research Report
└── README.md

```

## 📜 Abstract

> "Email phishing remains a critical cyber threat. This project proposes assessing whether deep learning models are capable of identifying phishing emails on a standardized set. Experimental findings on 145,000+ emails show that the models—specifically charCNN-BERT, are highly effective in developing real-world solutions for phishing detection."

## 🤝 Contact & Credits

**Divya Kamila** [LinkedIn](https://www.linkedin.com/in/divya-kamila) | [GitHub](https://github.com/divya0702)

*This project was completed as part of the Graduate Engineering program at the University of Maryland, College Park.*
