🐦 Twitter Sentiment Analysis
This project analyzes customer service tweets using Natural Language Processing (NLP) and machine learning to classify text into positive, negative, and neutral sentiments — helping understand the overall mood and tone behind Twitter interactions.

📂 Dataset

Source: Twitter Customer Service Dataset
Contains real customer service tweets labeled across three sentiment polarities


🚀 Features

Loads and explores tweet data for sentiment distribution
Preprocesses text using tokenization, stopword removal, and negation handling
Applies VADER for rule-based sentiment scoring
Trains XGBoost and Logistic Regression classifiers
Tunes hyperparameters using GridSearchCV and RandomizedSearchCV
Evaluates models with accuracy, classification report, and confusion matrix
Visualizes results with word clouds and bar charts


🛠️ Tech Stack

Language: Python
NLP: NLTK, VADER, TF-IDF, CountVectorizer
Machine Learning: XGBoost, Logistic Regression
Visualization: Matplotlib, Seaborn, WordCloud
Environment: Jupyter Notebook / VS Code


📝 How to Run

Clone this repo

bashgit clone https://github.com/your-username/twitter-sentiment-analysis
cd twitter-sentiment-analysis

Install requirements

bashpip install -r requirements.txt

Open the notebook and run all cells

bashjupyter notebook

📊 Example Outputs

Sentiment distribution across positive, negative, and neutral classes
Word clouds showing most frequent words per sentiment category
Model accuracy and classification report for each algorithm