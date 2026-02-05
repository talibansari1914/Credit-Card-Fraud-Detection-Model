# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project implements a **Machine Learning based Credit Card Fraud Detection System** that identifies fraudulent transactions from genuine ones.<br>
Fraud detection systems are critical components in the **banking and financial industry** to prevent financial losses and ensure secure transactions.<br>

---

## 🎯 Problem Statement
To build a machine learning model that can accurately classify credit card transactions as:<br>
- **Legitimate (0)**<br>
- **Fraudulent (1)**<br>

---

## 📊 Dataset Description
- The dataset consists of **credit card transaction records**<br>
- Most features are **anonymized numerical variables (V1–V28)** for privacy protection<br>
- Additional features include:<br>
  - `Time`<br>
  - `Amount`<br>

**Target Variable:**<br>
- `Class`<br>
  - `0` → Normal Transaction<br>
  - `1` → Fraudulent Transaction<br>

---

## ⚠️ Dataset Size Notice
The dataset used in this project is **very large (~98 MB)** and therefore **not included in this repository**.<br>

📥 **Dataset Source (Kaggle):**  
The dataset must be downloaded manually from Kaggle due to GitHub file size limitations.<br>
After downloading, place the dataset file in the project directory before running the notebook.<br>

---

## 🛠️ Technologies & Tools Used
- **Programming Language:** Python  <br>
- **Libraries:**<br>
  - NumPy<br>
  - Pandas<br>
  - Scikit-learn<br>
  - Matplotlib / Seaborn (for analysis)<br>

---

## 🔄 Data Preprocessing
- Separation of features and target variable<br>
- Train-test split for model validation<br>
- Handling of numerical and imbalanced transaction data<br>

---

## 🤖 Model Used
### Logistic Regression
- Binary classification algorithm<br>
- Fast and interpretable<br>
- Common baseline model for fraud detection problems<br>

---

## 📈 Model Training & Evaluation
- Model trained using training dataset<br>
- Performance evaluated on unseen test data<br>
- Results indicate consistent learning behavior<br>

> Note: In real-world fraud detection systems, additional metrics such as Precision, Recall, and F1-score are critical.<br>

---

## 🔮 Prediction System
The trained model predicts whether a given transaction is:<br>
- **Fraudulent**<br>
- **Legitimate**<br>

This logic can be extended for real-time fraud monitoring systems.<br>

---

## 🚀 Project Workflow
1. Data Loading<br>
2. Data Understanding & Analysis<br>
3. Data Preprocessing<br>
4. Train-Test Split<br>
5. Model Training<br>
6. Model Evaluation<br>
7. Fraud Prediction<br>

---

## 📌 Key Highlights
- Real-world financial dataset<br>
- Exposure to imbalanced classification problems<br>
- Industry-relevant use case<br>
- End-to-end machine learning pipeline<br>

---

## 🔮 Future Improvements
- Use advanced models (Random Forest, XGBoost, Isolation Forest)<br>
- Handle class imbalance using SMOTE or undersampling<br>
- Evaluate using Precision, Recall, F1-score, ROC-AUC<br>
- Deploy using Flask or FastAPI<br>

---

## 👤 Author
**Abbu Talib Ansari**<br>
GitHub:https://github.com/talibansari1914<br>
---

## 📄 License
This project is open-source and intended for educational purposes.<br>
