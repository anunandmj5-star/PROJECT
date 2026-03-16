# 🏥 Diabetes Prediction System

## Overview

The **Diabetes Prediction System** is a Machine Learning web application built using **Python and Streamlit** that predicts whether a person is likely to have diabetes based on medical input parameters.

The application uses a **Support Vector Machine (SVM)** model trained on a diabetes dataset and provides risk predictions along with probability scores, risk analysis, and health recommendations through an interactive interface.

This project demonstrates the integration of **machine learning, data preprocessing, and interactive visualization** in a simple healthcare prediction system.

---

## Features

* Predict diabetes risk using Machine Learning
* Interactive **Streamlit web interface**
* Patient data input through sidebar controls
* Probability breakdown for diabetic and non-diabetic predictions
* Risk level gauge chart visualization
* Health risk factor analysis
* Personalized health recommendations
* Medical disclaimer for safe usage

---

## Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Joblib
* Plotly

---

## Project Structure

```
Diabetes-Prediction-Project
│
├── app.py
├── diabetes_prediction.py
├── diabetes_model.pkl
├── scaler_svm.pkl
├── dataset.csv
└── README.md
```

**File Description**

* `app.py` → Streamlit web application for diabetes prediction
* `diabetes_prediction.py` → Script used to train the machine learning model
* `diabetes_model.pkl` → Saved trained SVM model
* `scaler_svm.pkl` → Feature scaling object used for input standardization
* `dataset.csv` → Diabetes dataset used for training
* `README.md` → Project documentation

---

## Dataset Information

The model is trained on a diabetes dataset containing **768 samples** with the following medical attributes:

* Pregnancies
* Glucose Level
* Blood Pressure
* Skin Thickness
* Insulin
* Body Mass Index (BMI)
* Diabetes Pedigree Function
* Age

**Target Variable**

* `0` → Non-Diabetic
* `1` → Diabetic

---
## Install Required Libraries

```
pip install streamlit pandas numpy scikit-learn plotly joblib
```

---

## Train the Model

Before running the application, train the model using:

```
python diabetes_prediction.py
```

This will generate the following files:

* `diabetes_model.pkl`
* `scaler_svm.pkl`

---

## Run the Application

Start the Streamlit application:

```
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## How the System Works

1. The user enters patient information in the sidebar.
2. Input data is standardized using a **feature scaler**.
3. The trained **SVM model** predicts the diabetes risk.
4. The system displays:

   * Risk level
   * Prediction probability
   * Health indicators
   * Recommendations

---

## Example Input

| Feature        | Example |
| -------------- | ------- |
| Age            | 35      |
| Pregnancies    | 2       |
| Glucose        | 140     |
| Blood Pressure | 80      |
| BMI            | 28.5    |

---

## Output

The system provides:

* Diabetes Risk Prediction
* Probability Score
* Risk Level Visualization
* Health Factor Analysis
* Health Recommendations

---

## Medical Disclaimer

⚠️ This system is designed **for educational purposes only**.
It should **not be used as a substitute for professional medical advice, diagnosis, or treatment**.

Always consult a qualified healthcare professional for medical concerns.

---

## Future Improvements

* Add multiple machine learning algorithms
* Improve prediction accuracy
* Deploy using **Streamlit Cloud**
* Add dataset visualization dashboard
* Implement patient history tracking

---