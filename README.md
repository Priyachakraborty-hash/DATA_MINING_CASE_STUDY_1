🧠 Data Mining Case Study 1 — Sentiment Analysis on Movie Reviews
📚 Overview

This project was completed as part of the Data Mining course at Binghamton University (Fall 2024).
The goal was to build, compare, and evaluate multiple machine learning and deep learning models for binary sentiment classification of movie reviews (positive vs negative).

The case study highlights my ability to analyze unstructured textual data, apply NLP techniques, and present insights through reproducible experiments.

🎯 Objectives

Clean and preprocess raw textual data for machine learning.

Apply NLP feature extraction techniques (TF-IDF, Bag-of-Words).

Implement and compare classical ML models and neural networks.

Evaluate model performance using standard classification metrics.

Present findings through visualizations and performance summaries.

🧩 Dataset

Source: IMDB Movie Review Dataset (IMDB_Dataset.csv)

Samples: 50,000 labeled reviews

Labels: positive (1) | negative (0)

Split: 80 % train | 20 % test

Each review was preprocessed by removing stopwords, punctuation, and performing tokenization and lemmatization.

⚙️ Methodology
1. Data Preprocessing

Tokenization & text normalization

Stopword removal and lemmatization

TF-IDF & CountVectorizer representations

2. Models Implemented
Model	Key Technique	Accuracy
Logistic Regression	Baseline linear model	0.90
Linear SVC	Margin-based classifier	0.91
Multilayer Perceptron (MLP)	Deep neural network	0.91
K-Nearest Neighbors (KNN)	Non-parametric	0.76
Random Forest	Ensemble method	0.88
3. Evaluation Metrics

Accuracy

Precision, Recall, F1-Score

Confusion Matrix

ROC-AUC Curve

📊 Results & Insights

MLP and Linear SVC achieved the highest accuracy (≈ 0.91).

Logistic Regression remained strong with minimal tuning, proving its robustness for sparse NLP features.

Deep models benefited from TF-IDF normalization, but interpretability was slightly reduced.

Misclassifications mainly occurred for ambiguous or sarcastic reviews, highlighting NLP’s contextual limitations.

💡 Key Learnings

Learned to translate raw text into quantitative, model-ready features.

Understood the trade-offs between accuracy, complexity, and interpretability.

Gained hands-on experience with Scikit-learn, TensorFlow/Keras, and NLP preprocessing pipelines.

Strengthened skills in data storytelling, reporting, and visualizing performance metrics.

🛠️ Tech Stack

Languages: Python (3.9+)
Libraries: Scikit-learn, TensorFlow/Keras, Pandas, NumPy, Matplotlib, Seaborn
Tools: Jupyter Notebook, Google Colab, GitHub