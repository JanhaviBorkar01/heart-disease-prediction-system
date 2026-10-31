# ❤️ Heart Disease Prediction System

## 📌 Project Overview

The Heart Disease Prediction System is a Machine Learning-based application developed to predict the possibility of heart disease using patient health parameters.

The project uses a **Random Forest Classifier** trained on a patient dataset containing 10 health-related features. An interactive web interface is developed using **Streamlit**, allowing users to enter health parameters and view the model's prediction.

## 🎯 Objectives

- To analyse patient health parameters using Machine Learning.
- To develop a model for classifying heart disease into two classes.
- To integrate the trained model into a user-friendly web application.
- To demonstrate the application of Machine Learning in healthcare.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **Algorithm:** Random Forest Classifier
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Model Saving:** Joblib
- **Web Framework:** Streamlit
- **Development Platform:** Google Colab
- **Version Control:** GitHub
- **Deployment:** Streamlit Community Cloud

## 📊 Dataset Features

The model uses the following 10 input parameters:

1. Age
2. Gender
3. Smoking Status
4. BMI
5. Heart Rate
6. Blood Oxygen
7. Body Temperature
8. Systolic Blood Pressure
9. Diastolic Blood Pressure
10. ECG Raw ADC Reading

**Target Variable:**
- `0` – No Heart Problem
- `1` – Heart Problem

## ⚙️ Project Workflow

1. **Dataset Collection:** Collected patient health data.
2. **Data Preprocessing:** Prepared the dataset and encoded categorical variables.
3. **Exploratory Data Analysis:** Analysed the data using statistical methods and visualizations.
4. **Model Training:** Trained a Random Forest Classifier using 100 decision trees.
5. **Model Evaluation:** Evaluated the model using accuracy, precision, recall, F1-score and a confusion matrix.
6. **Model Saving:** Saved the trained model and scaler using Joblib.
7. **Web Application:** Developed an interactive interface using Streamlit.
8. **Deployment:** Deployed the application using Streamlit Community Cloud.

## 🤖 Machine Learning Model

The Random Forest Classifier was selected because it combines multiple decision trees to make a final classification.

The dataset was divided into:
- 80% Training Data
- 20% Testing Data

The model achieved **93.33% accuracy** on the test dataset.

## 🌐 Web Application

The Streamlit interface allows users to:
- Enter patient health parameters.
- Submit the details for prediction.
- View the predicted classification.
- View the model's estimated probability for Class 1.
- Review the input parameters used for prediction.

## 📁 Project Files

| File | Description |
|---|---|
| `streamlit_app.py` | Main Streamlit application |
| `heart_disease_model.pkl` | Saved Random Forest model |
| `heart_disease_scaler.pkl` | Saved feature scaler |
| `requirements.txt` | Required Python libraries |
| `README.md` | Project documentation |

## 🚀 Run the Project Locally

**Step 1:** Clone the repository.

```bash
git clone https://github.com/janhaviborkaracp/heart-disease-prediction-system.git
```

**Step 2:** Open the project folder.

```bash
cd heart-disease-prediction-system
```

**Step 3:** Install the required libraries.

```bash
pip install -r requirements.txt
```

**Step 4:** Run the Streamlit application.

```bash
streamlit run streamlit_app.py
```

## ⚠️ Disclaimer

This project is developed for academic and educational purposes only. The predictions are based on an experimental Machine Learning model and should not be considered a medical diagnosis or a substitute for professional medical advice.

## 👩‍💻 Project Information

**Project Title:** Heart Disease Prediction System Using Random Forest

**Domain:** Machine Learning and Healthcare

**Developed using:** Python and Streamlit

