## Description
This project combines natural language processing (NLP) with financial data to build a predictive model for stock price forecasting. It integrates sentiment analysis to gauge market sentiment from news headlines.

## Key Highlights
**Data Preparation:**

* Collected and merged DJIA News and historical stock price datasets.
* Cleaned and preprocessed data using regex and Python libraries (pandas, numpy).

**Sentiment Analysis:**

* Used TextBlob for subjectivity and polarity scoring of news headlines.
* Employed VADER Sentiment Analysis for compound, negative, neutral and positive sentiment scores.

**Feature Engineering:**

* Created a consolidated dataset combining stock market features (Open, High, Low, Volume) with sentiment scores.
* Prepared feature set and labels for model training.

**Model Training and Evaluation:**

* Split data into training and testing sets (80/20 split).
* Trained a Linear Discriminant Analysis (LDA) model to predict stock price movements.
* Evaluated model performance using precision, recall and F1-score metrics.

## Tools and Technologies
Python, pandas, numpy, scikit-learn, TextBlob, VADER Sentiment Analysis, Google Colab.
