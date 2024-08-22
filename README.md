# IMDB Sentiment Analysis Project

## Overview

This project aims to perform sentiment analysis on movie reviews from the IMDB dataset. It involves preprocessing the data, applying machine learning algorithms, and evaluating their performance. We use different feature extraction techniques like Bag of Words (BOW), N-grams, and TF-IDF to train models and compare their accuracy.

## Project Structure

- **IMDB Dataset:** The dataset used in this project consists of movie reviews with their corresponding sentiment labels (positive/negative).
- **Preprocessing:** Includes removing HTML tags, converting text to lowercase, and removing stopwords.
- **Feature Extraction:** Implemented using Bag of Words, N-grams, and TF-IDF techniques.
- **Modeling:** Two machine learning models are implemented:
  - **Gaussian Naive Bayes**
  - **Random Forest Classifier**
- **Evaluation:** The models are evaluated using accuracy score, confusion matrix, and classification report.

## Dependencies

- `pandas`
- `nltk`
- `scikit-learn`
- `numpy`
- `re`

Make sure to install the necessary dependencies by running:

```bash
pip install pandas nltk scikit-learn numpy
