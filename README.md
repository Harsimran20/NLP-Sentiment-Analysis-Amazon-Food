# Amazon Fine Food Reviews Sentiment Analysis 🍎🍔🛒

## Overview

This project performs **sentiment analysis** on the Amazon Fine Food Reviews dataset using Natural Language Processing (NLP) techniques. It classifies reviews as **positive** or **negative** based on their text content and uncovers key topics through **topic modeling**.

---

## 🚀 Features

- **Data Preprocessing:** Clean and lemmatize review texts, remove stopwords and irrelevant characters
- **Sentiment Labeling:** Convert review scores (1-5) into sentiment classes: Positive, Negative (neutral reviews excluded)
- **Vectorization:** Use TF-IDF to convert text data into numerical features
- **Sentiment Classification:** Train and evaluate a Logistic Regression model to classify sentiment
- **Topic Modeling:** Discover latent topics in reviews with Latent Dirichlet Allocation (LDA)
- **Visualizations:**
  - Confusion matrix for classification results 📊
  - Word clouds for positive and negative reviews ☁️
  - Interactive LDA topic visualization using pyLDAvis 🔍

---

## 📁 Dataset

- Source: Amazon Fine Food Reviews dataset  
- Columns used:  
  - `Text`: The review text  
  - `Score`: Rating from 1 to 5  

---

## 🛠️ Installation & Setup

Make sure to install the required Python packages before running the code:

pip install pandas numpy scikit-learn nltk gensim matplotlib seaborn wordcloud pyLDAvis
You will also need to download some NLTK resources:

import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
📊 How to Run
Load the dataset

Clean and preprocess the text data

Create sentiment labels from review scores

Vectorize texts using TF-IDF

Train Logistic Regression classifier and evaluate performance

Run LDA for topic modeling on cleaned reviews

Generate visualizations (confusion matrix, word clouds, LDA topics)

🔍 Results & Visualizations
Classification performance metrics (precision, recall, F1-score)

Confusion matrix heatmap showing model accuracy

Word clouds highlighting frequent terms in positive vs. negative reviews

Interactive pyLDAvis plot to explore topics uncovered by LDA


📜 License
This project is open-source under the MIT License.
