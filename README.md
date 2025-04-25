# 💳 Credit Risk Prediction using Machine Learning

This project focuses on predicting the **credit risk** of loan applicants as either **Good** or **Bad**, helping financial institutions make informed lending decisions using demographic and financial data.

## 📊 Dataset

- **Source**: German Credit Data
- **Entries**: 1000
- **Features**:
  - Age, Sex, Job, Housing
  - Saving accounts, Checking account
  - Credit amount, Duration, Purpose
  - Risk (Target: Good/Bad)

## 🔍 Data Preprocessing

- Filled missing values in **Saving accounts** and **Checking account** using the **mode**.
- Used **Label Encoding** for categorical variables.
- Applied **StandardScaler** on numerical columns: Age, Credit Amount, and Duration.
- Split the dataset: **80% Training**, **20% Testing**.

## 🌲 Model

- **Algorithm**: Random Forest Classifier
- Trained on preprocessed data
- Evaluated using:
  - Accuracy: **70%**
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC: **0.77**

## 📈 Feature Importance

Top influential features:
- **Credit Amount**
- **Loan Duration**
- **Age**

Minimal impact from: **Sex** (desirable for fairness)

## 🧪 Streamlit App

An interactive Streamlit web app is in progress. Users can input features and receive real-time credit risk predictions.

## ✅ Conclusion

This project builds a complete machine learning pipeline for credit risk prediction — from data cleaning and model development to evaluation and feature interpretation.

---

### 🔧 Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit (for UI)

---

Feel free to fork, star ⭐, and contribute! 😊
