# PRISM-- Pretrained Representation with Index-conditioned Stock Modeling
# 🚀 PRISM: Market-Aware Fine-Tuning of Kronos for Stock Prediction

## 📌 Project Overview

PRISM is an end-to-end Financial AI project that fine-tunes the **Kronos Time-Series Foundation Model** for predicting **next-day stock returns** in the Indian stock market. The project combines **Financial Machine Learning**, **LLMs for Time Series**, and **Quantitative Finance** to build a complete stock ranking and portfolio backtesting pipeline.

---

## 🎯 Objectives

* Predict next-day stock returns
* Fine-tune Kronos using **LoRA / QLoRA**
* Learn market-aware stock representations
* Rank stocks based on predicted returns
* Build and evaluate a Long-Short investment strategy

---

## 📊 Dataset

* Indian Equity (NIFTY 500) historical data
* NIFTY 50 Index
* Daily OHLCV Data

  * Open
  * High
  * Low
  * Close
  * Volume

---

## ⚙️ Feature Engineering

The raw stock data is transformed into meaningful financial features:

* Daily Return
* Log Return
* Moving Averages (5, 10, 20 Days)
* Rolling Volatility
* Volume Change
* Volume Moving Average
* Rolling Beta
* Market Return
* Target (Next-Day Return)

---

## 🧠 Model Pipeline

```text
Raw Data
    ↓
Feature Engineering
    ↓
Sequence Generation
    ↓
Kronos Fine-Tuning (LoRA / QLoRA)
    ↓
Market-Gated Model
    ↓
Stock Return Prediction
    ↓
Stock Ranking
    ↓
Portfolio Backtesting
```

---

## 🤖 Deep Learning Components

* Kronos Time-Series Foundation Model
* LoRA / QLoRA Fine-Tuning
* Market-Gated Attention Module
* PyTorch DataLoader
* Transformer-based Sequence Modeling

---

## 📈 Evaluation Metrics

### Machine Learning

* MAE
* MSE
* RankIC

### Financial

* Sharpe Ratio
* Annual Return
* Maximum Drawdown
* Sortino Ratio
* Calmar Ratio

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Kronos
- PEFT (LoRA / QLoRA)
- Pandas
- NumPy
- Scikit-learn
- yFinance
- Matplotlib
- Streamlit
- Git & GitHub

---

## 📂 Project Workflow

* Data Collection
* Data Cleaning
* Feature Engineering
* Dataset Preparation
* Model Fine-Tuning
* Market Gating
* Model Evaluation
* Portfolio Backtesting
* Dashboard Development

---

## 🎯 Learning Outcomes

* Financial Machine Learning
* Time-Series Foundation Models
* Parameter-Efficient Fine-Tuning
* Transformer Architectures
* Quantitative Finance
* Portfolio Optimization
* End-to-End ML Pipeline Development

