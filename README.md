# NLP-fake-news-classifier
This project aims to detect fake news articles using Natural Language Processing (NLP) techniques and Machine Learning algorithms. It uses a dataset of labeled news articles to train a model, which can then predict whether a given news article is real or fake based on its content.

Table of Contents:
--------------------------------
Dataset
Features
Requirements
Installation
Usage
Results
Contributing
License
Dataset

The dataset used for this project is the Fake and Real News Dataset from Kaggle. It consists of two CSV files:
----------------------------------------------------
fake.csv: Contains labeled fake news articles.
real.csv: Contains labeled real news articles.
Features
The following NLP techniques and features are used for training the model:

TF-IDF Vectorization: Converts text data into numerical form.
N-grams: Captures word sequences to improve context understanding.
Text Cleaning: Removal of stopwords, punctuation, and lowercasing.
Feature Engineering: Length of the article, presence of certain keywords, etc.
Requirements:
-------------------
Python 3.x
Jupyter Notebook (for running the provided notebooks)
Libraries: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn
