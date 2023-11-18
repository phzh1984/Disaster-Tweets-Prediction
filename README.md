# Disaster-Tweets-Prediction

Twitter has emerged as a crucial communication channel during emergencies, enabling real-time reporting and sharing of critical information. Various organizations, including disaster relief agencies and news outlets, are increasingly interested in programmatically monitoring Twitter to identify and respond to potential disasters.

Overview

This project aims to predict whether a given tweet is about a real disaster or not. The dataset provided for this project includes the following information:

Text of the Tweet: Actual content of the tweet.

Keyword: Specific keyword(s) used in the tweet (may be blank in some cases).

Location: Location from where the tweet was sent (may be blank in some cases).

Target: Binary classification denoting whether the tweet is about a real disaster (1) or not (0). This column is available only in the training set (train.csv).

Data Format

Training Set (train.csv)

Columns:

id: Unique identifier for each tweet.

text: Textual content of the tweet.

location: Location from where the tweet was sent (may be blank).

keyword: Specific keyword(s) used in the tweet (may be blank).

target: Denotes whether a tweet is about a real disaster (1) or not (0).

Test Set (test.csv)

Similar columns without the target column, as it's what you're predicting.

Task

The goal is to build a machine learning model that accurately predicts whether a tweet is related to a real disaster or not based on the provided data.

To get started with this project:

Exploratory Data Analysis (EDA): Analyze the data, handle missing values, and explore relationships between features.

Model Building: Develop and train machine learning models to predict the target variable based on tweet text, keyword, and location.

Evaluation: Evaluate model performance using appropriate metrics and fine-tune as needed.

Prediction: Use the trained model to predict whether tweets in the test set are about real disasters or not.
