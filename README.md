# Salary-Prediction-

# 💼 Employee Salary Classification App

A simple machine learning web app that predicts whether an employee earns more than \$50K or not based on input features such as age, education, occupation, working hours, and experience.

Built using **Streamlit**, trained with **scikit-learn**, and deployable from **Google Colab** using **ngrok**.

---

## 📊 Features

- Predicts salary class: `>50K` or `<=50K`
- Supports both single input and batch prediction (via CSV)
- Uses best ML model chosen from multiple classifiers
- Clean and interactive UI with Streamlit
- Ready to deploy from Colab via ngrok

---

## 🚀 Tech Stack

| Tool           | Purpose                      |
|----------------|------------------------------|
| `Python`       | Core language                |
| `pandas`       | Data manipulation            |
| `scikit-learn` | ML model training/pipeline   |
| `Streamlit`    | Web app interface            |
| `joblib`       | Model saving/loading         |
| `ngrok`        | Public URL for Colab hosting |

---

## 🧠 Model Training

Models evaluated:
- Logistic Regression
- Random Forest
- K-Nearest Neighbors
- SVM
- Gradient Boosting

🔍 The best model (based on accuracy) is saved as `best_model.pkl` and used in the Streamlit app.

---

## 🗂️ Input Features

| Feature           | Description                        |
|-------------------|------------------------------------|
| `age`             | Age of the employee                |
| `education`       | Education level (categorical)      |
| `occupation`      | Type of job/role                   |
| `hours-per-week`  | Hours worked per week              |
| `experience`      | Years of experience                |

> ⚠️ These must match the columns used during training.

---

## 📂 File Structure

