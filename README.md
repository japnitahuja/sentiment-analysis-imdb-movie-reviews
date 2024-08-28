# Binary Sentiment Classification

## Problem Statement
Given a dataset of movie reviews, our goal is to build a model that accurately predicts the sentiment of each review. The dataset consists of 50,000 movie reviews, with 25,000 reviews designated for training and 25,000 for testing. The challenge is to classify each review as either positive or negative based on its content.

Kaggle Challenge: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## Approach

### Data Preprocessing

Cleaning Text: Remove any unnecessary characters, normalize the text, and handle missing values.

Label Encoding: Convert sentiment labels from "positive" and "negative" to numerical values (1 and 0, respectively).

### Feature Extraction

TF-IDF Vectorization: Convert the text data into numerical features using Term Frequency-Inverse Document Frequency (TF-IDF) to represent the importance of each word in the reviews.

### Model Training

Train test split: Split the data 50-50 randomly into train and test sets.

Model: Train a linear regression model on the data.

Predictions: Make predictions on the test set.

Performance Metrics: Evaluate the model using accuracy, precision, recall, and F1-score to assess its performance.
