# Amazon Fine Food Reviews Sentiment Analysis

## Overview
This project focuses on performing sentiment analysis on the Amazon Fine Food Reviews dataset using natural language processing (NLP) techniques. The dataset includes 568,454 reviews, involving 256,059 unique users and 74,258 unique products. The goal is to classify reviews as positive (rating 4 or 5) or negative (rating 1 or 2), ignoring neutral reviews (rating 3).

## Data Preparation
### Data Cleaning
- Removed duplicate and irrelevant entries.
- Handled missing values and inconsistencies in the dataset.

### Text Preprocessing
- **Stemming:** Reduced words to their base or root form.
- **Stop-word Removal:** Eliminated common words that do not contribute to the meaning of the text.
- **Lemmatization:** Converted words to their base or dictionary form.

## Feature Engineering
- **Bag of Words (BOW):** Represented text as a collection of words, disregarding grammar and word order but keeping multiplicity.
- **Term Frequency-Inverse Document Frequency (TF-IDF):** Measured the importance of a word in a document relative to a collection of documents.
- **Word2Vec (W2V):** Generated word embeddings to capture semantic relationships between words.

## Sentiment Analysis
- Developed a sentiment analysis model to classify reviews as positive (rating 4 or 5) or negative (rating 1 or 2).
- Implemented various text vectorization techniques to improve model performance.

## Tools and Libraries
- **Python Libraries:** NLTK, Scikit-learn, Pandas, NumPy
- **Machine Learning Models:** Naive Bayes, Support Vector Machines (SVM), Logistic Regression

## Results
- Achieved high accuracy in classifying reviews as positive or negative.
- Demonstrated the effectiveness of text vectorization techniques in improving model performance.

## References
- [Amazon Fine Food Reviews Sentiment Analysis Project](https://github.com/srivarshithdaladuli/Amazon-Fine-Food-Reviews-Sentiment_Analysis)
- [Amazon Fine Food Reviews Analysis using various ML models](https://github.com/kushagra414/Amazon-Fine-Food-Reviews-Analysis)
- [Data Preparation and Text-Preprocessing on Amazon Fine Food Reviews](https://medium.com/analytics-vidhya/data-preparation-and-text-preprocessing-on-amazon-fine-food-reviews-7b7a2665c3f4)

