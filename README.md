# Titanic-NLP-Survival-Prediction
This project uses Natural Language Processing (NLP) techniques to predict passenger survival on the Titanic dataset. Text data is cleaned, converted into numerical features using TF-IDF / CountVectorizer, and a machine learning classifier is trained to make predictions.
Text Cleaning

## Text data is preprocessed before modeling:

Convert text to lowercase

Remove punctuation

Remove stopwords (like “the”, “is”)

Tokenization (split text into words)

Lemmatization / Stemming (reduce words to root form)

This helps improve model performance.

## Feature Extraction

Since machine learning models need numbers, text is converted into numerical form using:

CountVectorizer – Converts text into word frequency counts.

TF-IDF – Assigns importance to words based on how frequently they appear.

TF-IDF usually performs better because it reduces the impact of common words.

## Train Classifier

Split data into training and testing sets

Train a model (Logistic Regression / Naive Bayes, etc.)

Predict survival on test data

## Evaluate Accuracy

Accuracy checks how many predictions are correct.

Accuracy = Correct Predictions ÷ Total Predictions

Example:
If 80 out of 100 predictions are correct → Accuracy = 80%

## Technologies Used

Python, Pandas, Scikit-learn, NLTK, Matplotlib / Seaborn

📊 Result

The model successfully predicts passenger survival using processed text features. TF-IDF showed better performance compared to basic word counts.
