# 📰 Automated Fake News Detection using Machine Learning

## 📌 Overview

Automated Fake News Detection is a machine learning project that classifies news articles as **Fake** or **Real** based on their textual content. The system uses Natural Language Processing (NLP) techniques to preprocess news articles and a machine learning classifier to predict their authenticity.

---

## 🚀 Features

* Detects whether a news article is **Fake** or **Real**
* Cleans and preprocesses news text
* Converts text into numerical features using **TF-IDF Vectorization**
* Uses **Passive Aggressive Classifier** for classification
* Provides fast and accurate predictions
* Easy to train with new datasets

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLP (Text Preprocessing)
* TF-IDF Vectorizer
* Passive Aggressive Classifier
* Jupyter Notebook

---

## 📂 Dataset

The project uses two CSV files:

* Fake.csv
* True.csv

Each dataset contains:

* News title
* News text
* Subject
* Date

The datasets are merged and labeled before training the model.

---

## ⚙️ Workflow

1. Load the datasets
2. Merge fake and real news
3. Assign labels
4. Clean and preprocess the text
5. Split the dataset into training and testing sets
6. Convert text into TF-IDF features
7. Train the Passive Aggressive Classifier
8. Evaluate model performance
9. Predict whether a new article is Fake or Real

---

