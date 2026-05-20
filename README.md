# 📈 Single Stock Prediction using Corporate Sentiment
![Python](https://img.shields.io/badge/Python-3.11-blue)

![XGBoost](https://img.shields.io/badge/Machine%20Learning-XGBoost-green)

![FinBERT](https://img.shields.io/badge/NLP-FinBERT-orange)

## Project Overview

This project predicts Tesla stock movement using corporate sentiment extracted from financial text sources and machine learning models.

Sentiment analysis was performed using FinBERT and RAG-based approaches.

The project combines financial sentiment with stock market indicators to evaluate predictive performance.

---

## Data Sources

### Financial Market Data
- Tesla historical stock prices (2015–2025)

### Corporate Text Data
- Earnings Call Transcripts
- SEC Filings (10-K / 10-Q)
- Financial News

---

## Sentiment Extraction

### FinBERT

Used for:

- Earnings Calls
- Financial News

Outputs:

- Positive sentiment
- Negative sentiment
- Neutral sentiment

### RAG Pipeline

Applied to:

- SEC documents
- Corporate reports

---

## Feature Engineering

Features:

- Previous Return
- 5-Day Volatility
- Earnings Sentiment
- SEC Sentiment
- News Sentiment

Target:

- Next-day stock return prediction

---

## Machine Learning Models

- Baseline
- Random Forest
- XGBoost
- LSTM

---

## Repository Structure

stock_sentiment_prediction/

data/
- raw/
- processed/

notebooks/

src/

results/
- figures/
- tables/

models/

docs/

---

## Technologies

Python

Pandas

NumPy

Scikit-Learn

XGBoost

PyTorch

Transformers

FinBERT

Matplotlib

---

## Author

Mario Jakupas

MS Computer Science – Data Analysis

Montclair State University
---

## Project Visualizations

### Tesla Historical Stock Price (2015–2025)

![Tesla Price](results/figures/tesla_stock_price_2015_2025.png)

### Earnings Call Sentiment Dataset

![Sentiment](results/figures/earnings_call_sentiment_dataset.png)

### XGBoost Feature Importance

![XGBoost](results/figures/xgboost_feature_importance.png)

### Model Performance Comparison

![Performance](results/figures/model_performance_comparison.png)

### LSTM Stock Prediction

![LSTM](results/figures/lstm_model_prediction.png)
