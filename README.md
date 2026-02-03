# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the presence of heart disease using patient medical data and a **Logistic Regression** machine learning model. The notebook is implemented in **Google Colab** using Python and focuses on data analysis, model training, and user-based prediction.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention.  
This project uses a supervised machine learning approach to classify whether a patient has heart disease based on selected health parameters.

---

## 📊 Dataset

- Dataset: `heart_disease.csv`
- Total records: **303**
- Features used:
  - `age` – Age of the patient
  - `cp` – Chest pain type (0–3)
  - `thalach` – Maximum heart rate achieved
- Target variable:
  - `target`  
    - `1` → Heart Disease  
    - `0` → No Heart Disease

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

- Summary statistics using `describe()`
- Pair plots for:
  - Age
  - Chest pain type
  - Maximum heart rate
  - Target variable

EDA helps understand relationships between features and the target.

---

## 🤖 Machine Learning Model

- Algorithm: **Logistic Regression**
- Data split:
  - 80% Training
  - 20% Testing
- Model training using `scikit-learn`

---

## 📈 Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve & AUC Score

These metrics help evaluate the performance of the model on unseen data.

---

## 🧑‍⚕️ User Input Prediction

The project includes a function that allows users to input:
- Age
- Chest pain type
- Maximum heart rate

Based on this input, the model predicts:
- **Heart Disease**
- **No Heart Disease**

---

## ▶️ How to Run the Project

1. Open the notebook in **Google Colab**
2. Upload `heart_disease.csv` when prompted
3. Run all cells sequentially
4. Enter user inputs when asked to get predictions

---

## 📂 Project Structure

