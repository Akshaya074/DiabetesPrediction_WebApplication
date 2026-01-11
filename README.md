# Diabetes Prediction Web Application

An end-to-end machine learning web application that predicts whether a person is diabetic based on key medical parameters. The application provides real-time predictions through an interactive web interface.

---

## 📌 Features
- Predicts diabetes using medical input parameters
- Real-time inference using a trained machine learning model
- Clean and interactive web interface built with Streamlit
- Deployed on Streamlit Community Cloud

---

## 🧠 Machine Learning Workflow
- Data preprocessing and numerical operations using NumPy
- Supervised classification model trained using Scikit-Learn
- Model serialization and loading using Pickle
- Prediction pipeline optimized for real-time inference

---

## 🧪 Input Parameters
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

---

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries:** NumPy, Scikit-Learn, Pickle
- **Web Framework:** Streamlit
- **Deployment:** Streamlit Community Cloud

---

## 📂 Project Structure
DiabetesPrediction_WebApplication/
│
├── app.py
├── trained_model.sav
├── requirements.txt
└── README.md


---

## ▶️ Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Akshaya074/DiabetesPrediction_WebApplication.git
cd DiabetesPrediction_WebApplication
pip install -r requirements.txt
streamlit run app.py

