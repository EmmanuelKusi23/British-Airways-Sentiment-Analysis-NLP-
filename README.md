# British Airways Sentiment Analysis (NLP) ✈️📊

![GitHub](https://img.shields.io/badge/Language-Python-blue)
![GitHub](https://img.shields.io/badge/Library-Scikit_Learn-orange)
![GitHub](https://img.shields.io/badge/Model-RoBERTa-purple)

## Overview
This project applies **Natural Language Processing (NLP)** techniques to analyze customer sentiment toward British Airways using Twitter data. The goal is to classify tweets as **Positive**, **Neutral**, or **Negative**, providing actionable insights into customer satisfaction and areas for improvement.

---

## Dataset 📁
- **Source**: Tweets mentioning British Airways, collected from Twitter.
- **Features**:
  - Textual content (customer reviews/complaints)
  - Timestamps, retweets, likes, and other metadata
- **Labels**: `Positive` | `Neutral` | `Negative`

---

## Methodology 🔍

### 1. Data Preprocessing
- **Text Cleaning**: Remove URLs, special characters, and whitespace.
- **Tokenization**: Split text into meaningful units (words/phrases).
- **Stopword Removal**: Filter out non-essential words (e.g., "the", "is").
- **Lemmatization**: Convert words to base forms (e.g., "running" → "run").

### 2. Sentiment Analysis Models
#### (a) VADER Sentiment Analysis ⚖️
- Lexicon-based approach optimized for social media text.
- Calculates polarity scores (`Negative`, `Neutral`, `Positive`, `Compound`).

#### (b) RoBERTa (Transformer Model) 🤖
- Fine-tuned pre-trained RoBERTa model for higher accuracy.
- Leverages deep learning to capture contextual nuances.

### 3. Model Evaluation 📈
- **Metrics**: Accuracy, Precision, Recall, F1-Score.
- **Comparative Analysis**: RoBERTa vs. VADER performance.

---

## Key Findings & Insights 💡
- **Sentiment Distribution**: 
  - Majority of tweets were **Negative** (common issues: delays, lost luggage, poor service).
- **Model Performance**:
  - RoBERTa outperformed VADER, demonstrating the power of transformer models.
- **Top Complaints**:
  - Flight delays (48% of negative tweets).
  - Baggage handling issues (32%).
  - Customer service dissatisfaction (20%).

---

## Recommendations 🚀
- Improve customer service responsiveness via AI chatbots.
- Address systemic causes of flight delays.
- Implement real-time baggage tracking systems.

---

## Getting Started 🛠️

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/EmmanuelKusi23/British-Airways-Sentiment-Analysis.git
   cd British-Airways-Sentiment-Analysis

Results Visualization 📊
Sentiment Distribution: Bar charts and word clouds.

Model Comparison: Accuracy and F1-score graphs.

Word Cloud Example Example: Frequent terms in negative reviews

Contributors 👥
Emmanuel Kusi
📧 emmadata287uk@gmail.com
🔗 LinkedIn Profile
🐙 GitHub Profile
