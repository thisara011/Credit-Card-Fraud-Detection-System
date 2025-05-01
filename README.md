# 💳 Credit Card Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![Imbalanced-Learn](https://img.shields.io/badge/Imbalanced_Learn-0.9.0-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A machine learning-based system to detect fraudulent credit card transactions using Logistic Regression and Random Forest algorithms. Designed to handle highly imbalanced datasets with PCA-transformed features.

## 📌 Key Features
- **Handles Class Imbalance**: Uses AUPRC (Area Under Precision-Recall Curve) for meaningful evaluation.
- **PCA-Optimized Features**: Analyzes 28 principal components (V1-V28) + Time/Amount.
- **Two ML Models**: 
  - **Logistic Regression** (Baseline)
  - **Random Forest** (Advanced ensemble)
- **Research-Backed**: Includes a companion research paper with methodology and results.

## 📊 Dataset Overview
- **Source**: European cardholders (Sept 2013, 2 days of transactions).
- **Size**: 284,807 transactions (492 frauds → 0.172% positive class).
- **Features**:
  - `V1-V28`: PCA-transformed numerical features.
  - `Time`: Seconds elapsed since first transaction.
  - `Amount`: Transaction amount.
  - `Class`: `1` (Fraud) / `0` (Legitimate).

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
