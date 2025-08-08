# Sentiment Analysis of Traveloka App Reviews

This project aims to perform sentiment analysis on user reviews of the Ajaib app collected from the Google Play Store.

## 📌 Features
- Text preprocessing (cleaning, case folding, tokenizing, filtering, etc.)
- Feature extraction using TF-IDF and Word2Vec
- Machine learning models: SVM, Random Forest, Logistic Regression
- Deep learning model: LSTM
- Model accuracy evaluation
- Inference/prediction of sentiment from new reviews

## 📊 Dataset
The dataset consists of cleaned and labeled Ajaib app reviews:
- Labels: Positive, Negative, Neutral
- Total entries: ~100,000 reviews

## ⚙️ Models Used
| Model              | Feature Extraction | Data Split | Train Accuracy | Test Accuracy |
|-------------------|--------------------|------------|----------------|----------------|
| SVM               | TF-IDF             | 80/20      | 91%            | 88%            |
| Random Forest     | Word2Vec           | 80/20      | 93%            | 85%            |
| Random Forest     | TF-IDF             | 70/30      | 94%            | 87%            |
| LSTM              | Tokenizer          | 80/20      | 95%            | 84%            |

## 📦 Installation
```bash
pip install -r requirements.txt
