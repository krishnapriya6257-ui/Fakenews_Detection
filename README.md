# Fakenews_Detection
Fake News Detection using Logistic Regression and TF-IDF

Objective:
This project aims to classify news articles as Fake or Real using a simple machine learning pipeline. It demonstrates how to take raw news text, preprocess it, convert it into numerical features, train a model, and evaluate its performance. The goal is to build a working NLP classifier that can predict the authenticity of news.

Dataset:
The dataset comes from Kaggle: Fake News Dataset
Fake.csv – contains fake news articles
True.csv – contains real news articles

Model Used:
Logistic Regression: A simple and effective model for binary classification
TF-IDF Vectorization: Converts text into numerical features highlighting important words

Accuracy:
The model achieves around 98% accuracy on the test set. Detailed metrics such as precision, recall, F1-score, and a confusion matrix are also included in the notebook.

How to Run:
Open Google Colab (https://colab.research.google.com)
Upload the notebook Fake_News_Detection.ipynb
Make sure the dataset CSV files (Fake.csv and True.csv) are available in the Colab environment
Run the cells sequentially from top to bottom

The notebook will train the model and show:
Accuracy
Classification report
Confusion matrix
To test your own news text, modify the news variable in the notebook and run the prediction cell. The model will tell you if it is Fake or Real.
