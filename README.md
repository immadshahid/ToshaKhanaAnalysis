# 🏛 Toshakhana Data Analysis & Gift Retention Prediction

This project analyzes historical Toshakhana gift records, cleans the data, generates insights and visualizations, and builds a predictive machine learning model to forecast whether a gift is likely to be **Retained** or **Deposited**.

## 📂 Dataset

- **Source**: `Toshakhana Files 2.xlsx`
- **Contents**: Gift details, recipient names, remarks on retention, etc.
- **Timeframe**: Since 2002

---

## 🚀 Features

### ✅ Data Cleaning & Preprocessing
- Extracts relevant columns
- Handles missing values and inconsistent formatting
- Combines useful textual features

### 📊 Exploratory Data Analysis
- Top recipients of gifts
- Common types of gifts
- Distribution of remarks (Retained vs Deposited)
- Bar charts using Matplotlib & Seaborn

### 🔮 Machine Learning Prediction
- Goal: Predict whether a gift will be **Retained**
- Features used: `Gift Description + Recipient Name`
- Model: Logistic Regression with TF-IDF
- Evaluation: Classification report and confusion matrix

---

## 🧪 How to Run

### 1. Upload the Excel File
```bash
Toshakhana Files 2.xlsx  ➜  /content/ in Google Colab
