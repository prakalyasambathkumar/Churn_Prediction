# 🧠 Bank Customer Churn Prediction

This project focuses on predicting whether a customer will leave a bank (churn) using machine learning techniques. The model was built and trained in a Google Colab notebook using a real-world dataset.

---

## 📌 Overview

- Developed a machine learning model to predict customer churn.
- Trained and evaluated multiple models including:
  - Logistic Regression
  - Random Forest
  - LightGBM (best performing)
- Performed exploratory data analysis (EDA), preprocessing, feature selection, and model tuning.

---

## 📁 Files

- `churn_model.ipynb` – Main Google Colab notebook with:
  - Data preprocessing
  - Model training and evaluation
  - Performance comparison
- `churn_model.pkl` (optional) – Exported trained model using `joblib` for future deployment.

---

## 📊 Dataset

- **Source**: [Kaggle - Predicting Churn for Bank Customers](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)
- Contains customer information like:
  - Credit score
  - Age
  - Tenure
  - Balance
  - Number of products
  - Active membership
  - Estimated salary
  - Geography and gender

---

## ✅ Model Performance

- **Best Model**: LightGBM
- **Accuracy**: ~**XX%** (replace with your result)
- **F1 Score**: ~**YY%** (optional)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- LightGBM
- Matplotlib, Seaborn
- Google Colab

---

## 🚀 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the dataset (`Churn_Modelling.csv`).
3. Run all cells to train and evaluate the models.
