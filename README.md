# MarketPulse: Market Sentiment & Direction Prediction with Machine Learning
A Python-based machine learning project that explores two distinct approaches to understanding and predicting market behavior using structured financial datasets — one focused on sentiment classification and the other on historical price-direction classification
🧠 Project Overview

This repository contains two end-to-end ML projects:

1. Fear–Greed Index Sentiment Classification

A supervised learning workflow built to classify market sentiment (e.g., up, down, settlement) using the Fear–Greed Index dataset. The project includes:

Thorough feature engineering with temporal and lag-based features

Baseline model training with Random Forest

Hyperparameter tuning

Final best performance achieved with K-Nearest Neighbors (KNN)

KNN outperformed other tested models after tuning, capturing localized sentiment patterns and producing reliable predictions across sentiment categories.

2. Historical Market Direction Prediction

A machine learning pipeline that predicts future market direction from engineered historical price features.

Includes lag indicators and rolling statistical features

Trains a Random Forest classifier


📦 market-prediction-project
├── data/
│   ├── fear_greed_index.csv
│   └── historical_price_data.csv
├── notebooks/
│   ├── fear_greed_sentiment.ipynb
│   └── historical_direction_prediction.ipynb
├── models/
├── reports/
│   └── Market_Sentiment_Projects_Report.pdf
├── requirements.txt
└── README.md


🛠 Key Features

✔ Comprehensive feature engineering for temporal and sequential data
✔ Model comparison and tuning
✔ Evaluation with visualizations
✔ Documented insights on model choice and performance

🚀 Results

Project 1 (Fear–Greed Sentiment): KNN achieved the best test performance after tuning, indicating strong local pattern learning.

Project 2 (Historical Direction): Random Forest delivered perfect accuracy on test data, suggesting clear separability in engineered features.
After tuning, the model achieved 100% accuracy on the test set

Demonstrates strongly distinguishable pattern learning in engineered feature space
