💓 Heart Disease Prediction App
A machine learning web application built with Streamlit that predicts the risk of heart disease based on a person’s health data.
This project uses the Logistic Regression algorithm and the Heart Disease UCI dataset from Kaggle.

🧠 Overview
Heart disease is one of the leading causes of death worldwide. Early detection through predictive modeling can help save lives.
This app takes patient data (such as age, cholesterol level, and blood pressure) and predicts the likelihood of having heart disease.

⚙️ Features

. Interactive Streamlit web interface

. Real-time prediction of heart disease risk

. Uses Logistic Regression for classification

. Displays prediction confidence percentage

. Easy to use and deploy locally or on the web

📁 Project Structure
📂 Heart_Disease_Prediction
│
├── heart_disease_app.py     # Main Streamlit application
├── heart.csv                 # Dataset (from Kaggle)
├── heart_model.pkl           # Saved machine learning model
├── requirements.txt          # Required libraries
└── README.md                 # Project documentation

🧩 Tools and Libraries Used

Python

Pandas – Data manipulation

NumPy – Numerical operations

Scikit-learn – Machine Learning (Logistic Regression, train-test split, accuracy)

Streamlit – Building the web interface

Joblib – Saving and loading trained models

Matplotlib / Seaborn (optional) – For visualization

🧮 Model Details

Algorithm: Logistic Regression

Train-Test Split: 80% training, 20% testing

Evaluation Metric: Accuracy Score

Saved Model File: heart_model.pkl


🏁 Output

“✅ Low risk of heart disease” – if model predicts 0

“⚠️ High risk of heart disease” – if model predicts 1

Displays confidence percentage of the prediction.



