# FakeReviewDetection
# 🧠 Fake Review Detection using NLP and SVM

This project uses Natural Language Processing (NLP) techniques and a Support Vector Machine (SVM) classifier to identify fake or genuine product reviews.

## 📄 Overview

With the surge in online shopping, fake reviews can mislead customers and harm brand reputation. This project aims to automate the detection of such reviews using text-based analysis and machine learning.

---

## 📁 Dataset

- Source: `fake-reviews-dataset.xlsx`
- Columns: 
  - `text_` — the original review
  - `label` — CG (credible/genuine), OR (opinion/spam)
  - `category` and `rating` (additional metadata)

---

## 🔍 Features

- **Text Preprocessing**: 
  - Lowercasing, punctuation removal
  - Tokenization, stopword removal
  - Stemming and lemmatization using NLTK

- **Feature Extraction**:
  - Bag of Words (BoW) model
  - TF-IDF transformation

- **Model**: 
  - Linear Support Vector Machine (SVM)

- **Evaluation**:
  - Accuracy: ~87%
  - Includes confusion matrix and classification report

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

