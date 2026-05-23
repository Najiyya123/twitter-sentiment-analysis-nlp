# 🐦 Twitter Sentiment Analysis

This project applies Natural Language Processing (NLP) and machine learning techniques to classify Twitter texts into **positive**, **negative**, and **neutral** sentiments. It explores how textual data can be analyzed to uncover emotional tone and opinion patterns at scale.

---

## 📂 Dataset

- Source: [Twitter Customer Service Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-GPXX0DYDEN/twitterv3.csv)
- Contains real customer service tweets labeled across three sentiment polarities

---

## 🚀 Features

- Loads and explores tweet data for sentiment distribution
- Preprocesses text using tokenization, stopword removal, and negation handling
- Applies VADER for rule-based sentiment scoring
- Trains XGBoost and Logistic Regression classifiers
- Tunes hyperparameters using GridSearchCV and RandomizedSearchCV
- Evaluates models with accuracy, classification report, and confusion matrix
- Visualizes results with word clouds and bar charts

---

## 🛠️ Tech Stack

- **Language:** Python
- **NLP:** NLTK, VADER, TF-IDF, CountVectorizer
- **Machine Learning:** XGBoost, Logistic Regression
- **Visualization:** Matplotlib, Seaborn, WordCloud
- **Environment:** Jupyter Notebook / VS Code

---

## 📝 How to Run

1. Clone this repo
\```bash
git clone https://github.com/your-username/twitter-sentiment-analysis
cd twitter-sentiment-analysis
\```

2. Install requirements
\```bash
pip install -r requirements.txt
\```

3. Open the notebook
\```bash
jupyter notebook
\```

---

## 📊 Example Outputs

- Sentiment distribution across positive, negative, and neutral classes
- Word clouds showing most frequent words per sentiment category
- Model accuracy and classification report for each algorithm

---

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/twitter-sentiment-analysis/blob/main/sentiment%20analysis.ipynb)
