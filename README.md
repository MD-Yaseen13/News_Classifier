# News Classification Project

## Overview

This project aims to classify news articles as either fake or true using machine learning techniques. The classification is performed based on the content of the articles. The model leverages Natural Language Processing (NLP) and machine learning algorithms to achieve accurate results.

## Project Components

1. **Datasets:**
   - **Fake.csv:** Contains news articles labeled as fake.
   - **True.csv:** Contains news articles labeled as true.

2. **Jupyter Notebook:**
   - **`news_classification.ipynb`:** The main notebook that includes:
     - Data loading and exploration
     - Data cleaning and preprocessing
     - Feature extraction using TF-IDF
     - Model training with Logistic Regression
     - Evaluation of model performance
     - Predictions on new data

## Key Steps

1. **Data Preparation:**
   - Combine and clean the datasets.
   - Remove stopwords and unnecessary characters from the text.

2. **Feature Extraction:**
   - Use TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical features.

3. **Model Training:**
   - Train a Logistic Regression model to classify news articles.

4. **Evaluation:**
   - Assess the model's accuracy and performance using metrics such as precision, recall, and F1-score.

5. **Prediction:**
   - Use the trained model to classify new, unseen news articles.

