# 🧠 DRW Crypto Market Prediction 🚀

[![Kaggle Competition](https://img.shields.io/badge/Kaggle-DRW%20Crypto%20Prediction-blue)](https://www.kaggle.com/competitions/drw-crypto-market-prediction)

This repository contains a complete end-to-end pipeline to predict crypto market price movements as part of the **DRW Crypto Market Prediction** competition on Kaggle.

---

## 🔮 Problem Overview

Crypto markets are complex, volatile, and prone to anomalies. The goal of this project is to predict price movements using high-frequency trading data through robust data preprocessing, anomaly detection, and machine learning modeling.

---

## 📦 Key Components

### 1. 🧼 Data Cleaning & Preprocessing
- Handles missing values and infinite values.
- Detects temporal anomalies using Facebook Prophet.
- Applies statistical correction using Isotonic Regression.

### 2. 🔍 Anomaly Detection
- Prophet time-series modeling on key features.
- Correction strategies derived from anomaly scores and Prophet bounds.
- Visual diagnostics included.

### 3. ⚙️ Feature Engineering
- Derived over 40+ features from order book data and market microstructure.
- Scaled inputs using `RobustScaler` to handle outliers.

### 4. 🤖 Machine Learning Model
- Utilized **XGBoost** for regression.
- Custom correction curve integration to optimize input reliability.
- Pearson correlation used for evaluation.

---

## 📊 Results

- Evaluated using **Pearson correlation coefficient** on the validation set.
- Modular design allows quick testing of alternate strategies.

---

## 📁 Files

| File | Description |
|------|-------------|
| `d-r-w-crypto-market-prediction.ipynb` | Full notebook with preprocessing, anomaly correction, training, and prediction |
| `crypto_predictions.csv` | Final submission file |
| `anomaly_insights.png` | Visualizations of anomaly corrections |

---

## 📷 Visual Example

![Anomaly Insights](anomaly_insights.png)

---

## 📌 How to Run

1. Clone the repo or open the notebook on Kaggle.
2. Upload the dataset provided by the competition.
3. Run the notebook end-to-end or call `execute_prediction_flow()` to generate the prediction file.

---

## 🧠 Author

**Dur-e-Yashfeen**  
👩‍💻 AI/ML Engineer | Data Science Enthusiast | Kaggle Competitor

---

## 🔗 Competition Link

👉 [DRW Crypto Market Prediction on Kaggle]([https://www.kaggle.com/competitions/drw-crypto-market-prediction](https://www.kaggle.com/competitions/drw-crypto-market-prediction)
n)

---

## ⭐️ If you find this useful, consider giving it a star!
