# fake-news-detection-model
This is a model which predicts whether the news is fake or true

# 📰 Fake News Detection System

A machine learning model that classifies news articles as "real" or "fake" with 99.6% accuracy using NLP techniques.

![Demo](https://img.shields.io/badge/Accuracy-99.6%25-brightgreen) 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

## 🚀 Features
- Text preprocessing pipeline (URL removal, HTML cleaning, etc.)
- TF-IDF vectorization for feature extraction
- Two classification models:
  - Logistic Regression (98.6% accuracy)
  - Decision Tree Classifier (99.6% accuracy)
- Detailed classification reports

## 📂 Dataset
Combined dataset from:
- `true.csv`: 21,417 real news articles
- `fake.csv`: 23,481 fake news articles

**Final Dataset Stats:**
- Total samples: 44,898
- Features: Processed text content
- Target: Binary label (0=fake, 1=real)

