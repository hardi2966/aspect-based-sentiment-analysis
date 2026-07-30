Aspect-Based Sentiment Analysis for Restaurant Reviews
📌 Project Overview

This project implements Aspect-Based Sentiment Analysis (ABSA) using Natural Language Processing (NLP) and Machine Learning. Unlike traditional sentiment analysis, which predicts the overall sentiment of a review, this project identifies specific aspects (such as Food, Service, Ambience, and Price) and predicts the sentiment associated with each aspect.

The model uses TF-IDF, Word2Vec, and BERT embeddings for feature extraction and compares multiple machine learning algorithms to classify sentiments as Positive, Negative, or Neutral.

🎯 Objectives
Perform text preprocessing on restaurant reviews.
Extract aspect-level information from reviews.
Convert text into numerical features using TF-IDF, Word2Vec, and BERT.
Train and compare multiple machine learning models.
Predict sentiment for a given review and aspect.
📂 Dataset

The dataset contains restaurant reviews with the following information:

Review Sentence
Aspect
Aspect Category
Sentiment Label

Each review may contain multiple aspects with their corresponding sentiments.

🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
NLTK
Scikit-learn
Gensim (Word2Vec)
Sentence Transformers (BERT)
Matplotlib
Joblib
🤖 Machine Learning Models
Logistic Regression
Naïve Bayes
Random Forest
Linear SVM
📊 Feature Extraction
TF-IDF
Word2Vec
BERT Embeddings
📈 Model Evaluation

The models are evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
🚀 Project Workflow
Load Dataset
Data Preprocessing
Aspect-Level Dataset Preparation
Feature Extraction (TF-IDF, Word2Vec, BERT)
Train-Test Split
Model Training
Model Evaluation
Sentiment Prediction
