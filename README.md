# Titanic-NLP-Survival-Prediction

NLP-based Titanic survival prediction using text preprocessing, TF-IDF vectorization, and Logistic Regression achieving 73.18% accuracy.
This project applies Natural Language Processing (NLP) techniques to predict passenger survival on the Titanic dataset. Text data is cleaned, transformed using TF-IDF vectorization, and used to train a Logistic Regression classifier.

The project demonstrates a complete NLP pipeline including preprocessing, feature extraction, model training, and evaluation.

## Dataset

Dataset: Titanic dataset

Target Variable: Survived (0 = No, 1 = Yes)

Text Feature Used: Passenger Name column

## Text Cleaning

The following preprocessing steps were applied:
Convert text to lowercase, Remove special characters, Remove stopwords, Tokenization, Lemmatization

## Feature Extraction (TF-IDF)

Text was converted into numerical format using TF-IDF (Term Frequency – Inverse Document Frequency).

TF-IDF helps assign importance to meaningful words while reducing the impact of common words.

## Model Training

Data split into training and testing sets (80:20)

Logistic Regression classifier trained on TF-IDF features

##  Model Evaluation

The model was evaluated using Accuracy, Classification Report, and Confusion Matrix.

## Model Performance

Accuracy: 73.18%

Precision (Class 0): 0.70

Recall (Class 0): 0.95

Precision (Class 1): 0.86

Recall (Class 1): 0.42

🔎 Confusion Matrix
[[100   5]
 [ 43  31]]


This shows:

100 correct non-survival predictions

31 correct survival predictions

5 false positives

43 false negatives

## Technologies Used


Python, Pandas, Scikit-learn, NLTK, TF-IDF Vectorizer, Logistic Regression





