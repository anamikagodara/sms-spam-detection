# sms-spam-detection
NLP project to detect spam messages using python

-Project Overview

This project builds a machine learning model to classify SMS messages as Spam or Ham(not spam).
The goal is to automatically detect unwanted spam messages using Natural Language Processing (NLP) techniques.

-Technologies Used
1. Pandas 2.NLTK 3.Scikit-learn 4.NumPy 

-Project Workflow
1.Data Colllection
 The dataset conatins SMS messages labeled as:
   *Spam-unwanted promotional messages
   *Ham-normal messages

2.Data Preprocessing
  Text preprocessing steps include:
    *Converting text to lowercase
    *Removing special characters
    *Removing stopwords
    *Stemming words using NLTK

3. Feature Extraction
   Text data is converted into numercial fatures using:
   Bag of Words(BOW) with CountVectorizer.

4.Model Training
   The classification model used:
   Multinomial Naive Bayes
   This model works well for text classification problems.

5.Model Evaluation
   The model is evaluated using:
      *Accuracy Score
      *Classification report

6.Results
The model successfully classifies SMS messages into spam or ham with high accuracy


