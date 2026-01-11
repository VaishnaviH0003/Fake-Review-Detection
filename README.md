# Fake Review Detection System

This project implements a machine learning–based approach to detect suspicious or fake product reviews using the Amazon Fine Food Reviews dataset.

## 📌 Dataset
- Amazon Fine Food Reviews Dataset
- Total Reviews: 568,000+
- Source: Kaggle
- The dataset does not contain fake/genuine labels.

## 📌 Problem Statement
Online platforms suffer from fake reviews that mislead customers. Since real labels are unavailable, this project uses heuristic labeling to identify suspicious reviews and applies machine learning for classification.

## 📌 Methodology
1. Heuristic labeling based on:
   - Short 5-star reviews
   - Zero helpfulness positive reviews
   - Duplicate review text
2. Text preprocessing and cleaning
3. Feature extraction using TF-IDF and n-grams
4. Classification using Multinomial Naive Bayes
5. Model evaluation using confusion matrix and ROC curve
6. Graph-based user–product analysis to identify suspicious reviewer clusters

## 📌 Results
- ROC-AUC Score: 0.76
- Clear separation of suspicious and genuine review patterns
- Interpretable features via n-gram analysis
- Detection of coordinated reviewer behavior through graph analysis

## 📌 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- TF-IDF
- Matplotlib, Seaborn
- Google Colab

## 📌 Visualizations
The project includes:
- Confusion Matrix
- ROC Curve
- Word Clouds
- N-gram Analysis
- Label Distribution
- Graph-based Reviewer Network

## 📌 Disclaimer
The labels used in this project are heuristic-based and indicate suspicious patterns, not confirmed fake reviews.
