# ReviewPulse-Googleplay_REVIEW-
# Overview:
ReviewPulse is a Natural Language Processing (NLP) project that performs sentiment analysis on app names and their associated ratings from the Google Play Store dataset. The aim is to classify the sentiment as positive, negative, or neutral using machine learning techniques.
# Dataset:
The dataset used is googleplaystore.csv.zip, which includes various app metadata. This project focuses on:

    >App names (used as text data)

    >Ratings (used to generate sentiment labels)

Sentiment labels are assigned based on the rating:

    >Rating >= 4.0 → Positive

    >Rating < 3.0 → Negative

    >Rating between 3.0 and 3.9 → Neutral

# Project Workflow:

1-Load and clean the dataset

2-Filter rows with valid numeric ratings

3-Assign sentiment labels based on rating thresholds

4-Preprocess text using NLP techniques:

    >Lowercasing

    >Removing punctuation and stopwords

5-Vectorize the text using TF-IDF (Term Frequency-Inverse Document Frequency)

6-Split the data into training and test sets

7-Train a Logistic Regression model

8-Predict sentiments and evaluate the model using:

    >Accuracy Score

    >Classification Report

    >Confusion Matrix Heatmap

# Technologies and Libraries Used:

Python

pandas

numpy

matplotlib

seaborn

nltk (for text preprocessing)

scikit-learn (for modeling and evaluation)

# Output:

Cleaned dataset with sentiment labels

TF-IDF matrix for text features

Trained logistic regression model

Accuracy score printed on console

Confusion matrix heatmap

Classification report with precision, recall, and F1-score

# Project Structure:

googlereview.py – Main Python script

googleplaystore.csv.zip – Compressed dataset (must be downloaded manually)

README.txt – Project documentation
