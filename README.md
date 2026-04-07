# 💖 Heart Disease Prediction - End-to-End Machine Learning Project

## 📌 Project Overview

This project is an end-to-end machine learning application that predicts the likelihood of heart disease based on user input parameters such as age, cholesterol, blood pressure, and other medical attributes.

The system uses a trained machine learning model and provides predictions through an interactive web application built using Streamlit.

---

## 🚀 Features

* 🔍 User-friendly web interface
* 📊 Real-time prediction
* 🤖 Machine Learning model integration
* ⚙️ Data preprocessing & scaling
* 📈 End-to-end pipeline (EDA → Model → Deployment)

---

## 🧠 Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Joblib
* Streamlit

---

## 📂 Project Structure

```
├── app.py                  # Streamlit application
├── KNN_heart_model.pkl     # Trained ML model
├── heart_scaler.pkl        # Data scaler
├── expected_columns.pkl    # Feature columns
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

## 📊 Dataset Information

The model is trained on a heart disease dataset containing features like:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* ECG Results
* Maximum Heart Rate
* Exercise-induced Angina
* Oldpeak
* ST Slope

These features help predict whether a person is at risk of heart disease. ([Infinity Codex][1])

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/aryangandhale27-cell/Heart-Desease-prediction-end-to-end-.git
cd Heart-Desease-prediction-end-to-end-
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the application

```
streamlit run app.py
```

---

## 🖥️ Usage

1. Enter patient details in the form
2. Click on **Predict**
3. View prediction result instantly

---

## 📈 Model Details

* Algorithm: K-Nearest Neighbors (KNN)
* Data preprocessing: Scaling + Encoding
* Output:

  * 0 → Low Risk
  * 1 → High Risk

---

## ⚠️ Disclaimer

This project is for educational purposes only.
It should NOT be used for real medical diagnosis.

---

## 📌 Future Improvements

* Improve model accuracy
* Add multiple ML models
* Deploy on cloud (Streamlit Cloud / AWS)
* Add visualization dashboards

---

## 👨‍💻 Author

**Aryan Gandhale**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

[1]: https://www.infinitycodex.in/2020/10/heart-disease-prediction-end-to-end.html?utm_source=chatgpt.com "Heart Disease Prediction End to End Machine Learning Project (Model Creation) - InfinityCodeX"
