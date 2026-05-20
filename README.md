# Restaurant Review Sentiment Analyzer 🍽️

A simple and effective **Sentiment Analysis** project that predicts whether a restaurant review is **Positive** or **Negative** using Machine Learning.

![Accuracy](https://img.shields.io/badge/Accuracy-78.5%25-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![scikit--learn](https://img.shields.io/badge/scikit--learn-latest-orange)

---

## 📋 Project Overview

This project analyzes customer restaurant reviews and automatically classifies them as **Positive** 👍 or **Negative** 👎.

It uses **Natural Language Processing (NLP)** techniques and **Multinomial Naive Bayes** algorithm. The model was trained on 1000 restaurant reviews and achieved a maximum accuracy of **78.5%**.

---

## ✨ Features

- Text cleaning and preprocessing
- Stopword removal and stemming
- Bag of Words vectorization
- Naive Bayes model with hyperparameter tuning
- Easy-to-use prediction function
- Good accuracy for a classic ML model

---

## 📊 Dataset

- File: `Restaurant_Reviews.tsv`
- Total Reviews: **1000**
- Columns: `Review`, `Liked` (1 = Positive, 0 = Negative)

---

## 🛠️ Technologies Used

- **Python**
- Pandas & NumPy
- NLTK (Text Processing)
- Scikit-learn (Machine Learning)
- Matplotlib & Seaborn (Visualization)

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/restaurant-review-sentiment-analyzer.git
cd restaurant-review-sentiment-analyzer
