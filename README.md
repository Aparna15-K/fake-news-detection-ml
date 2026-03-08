
# Fake News Detection using NLP

## Project Description
This project classifies news articles as Fake or Real using NLP.
The goal is to automatically detect fake news using machine learning techniques.

## Dataset
- Fake.csv : Contains fake news articles
- True.csv : Contains real news articles

## Features
- Text cleaning and preprocessing
- TF-IDF feature extraction
- Model training using PassiveAggressiveClassifier
- Accuracy evaluation and confusion matrix visualization
- Interactive widget to test any news headline

## How to Run
1. Open fake_news_detection.ipynb in Google Colab
2. Upload Fake.csv and True.csv
3. Run all cells sequentially
4. Use the Test News Input Widget to check if a headline is Fake or Real

## Notes
- Model accuracy: ~92% (may vary depending on data)
- Some headlines may be misclassified due to limited context
