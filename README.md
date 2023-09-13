# Twitter Sentiment Analysis

This project aims to analyze the sentiment of tweets using natural language processing (NLP) techniques and machine learning models.

## Motivation

Twitter is one of the most popular social media platforms where people express their opinions, feelings, and thoughts on various topics. Sentiment analysis is the task of automatically identifying and extracting the polarity (positive or  negative) of text. It can be useful for various applications, such as marketing, customer service, product reviews, and social media monitoring.

# Overview

The project consists of the following steps:

## 1. Data collection:
 We used a kaggle dataset which can be accessed through this link https://www.kaggle.com/c/twitter-sentiment-analysis2
 <img src = "https://github.com/Farah-DeebaJ/TwitterSentimentAnalysis/blob/main/VisualCharts/comparison.png" alt ="pos_neg chart">
 </br>
  <img src = "https://github.com/Farah-DeebaJ/TwitterSentimentAnalysis/blob/main/VisualCharts/compare.png" alt ="pos_neg chart">
## 2.  Data preprocessing: 
This is a paragraph that summarizes the steps involved in preprocessing the input tweet for sentiment analysis:

Preprocessing is the process of modifying the input tweet in a format that can be given to the classifier. It involves several steps, such as:

- Removing hashtags, which are words or phrases preceded by a hash sign (#) that identify messages on a specific topic. Hashtags do not provide any information about the sentiment of the text.
- Removing URLs, which are used to share links to other sites in tweets. URLs do not provide any information about the sentiment of the text either.
- Removing emoticons, which are symbols or icons that represent human expressions. Emoticons are very much used nowadays in social networking sites, but their usefulness for sentiment analysis remains part of the future work.
- Removing punctuations, which are marks or signs that separate sentences or parts of sentences. Punctuations do not affect the sentiment of the text and can be removed without changing its meaning.
- Removing repeating characters, which are characters that are repeated more than twice in a word. Repeating characters do not add any value to the text and can be reduced to a single occurrence.
- Stemming, which is the process of reducing words to their root or base form. Stemming helps to normalize the text and reduce the vocabulary size. A stemmer for English, such as Porter stemmer, can identify the root word of different forms of the same word, such as "fishing", "fished", and "fisher".
## 3. Data exploration: 
We perform some exploratory data analysis on the tweets, such as word frequency, word cloud, sentiment distribution, and n-gram analysis.
## 4. Data modeling:
 We train and evaluate different machine learning models for sentiment analysis, such as logistic regression, naive Bayes, support vector machine, and random forest.

## Requirements

The project requires the following Python packages:

- pandas
- numpy
- nltk
- scikit-learn
- matplotlib
- seaborn

