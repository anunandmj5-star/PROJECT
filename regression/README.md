# 🎓 Student Exam Result Prediction System

## Overview

The **Student Exam Result Prediction System** is a machine learning web application built using **Python and Streamlit** that predicts a student's expected exam score based on academic and lifestyle factors.

The system uses a trained machine learning model to analyze inputs such as study hours, attendance, sleep habits, and mental health. Based on these factors, the model predicts the student's likely exam score.

This project demonstrates how **machine learning can be applied in education to analyze student performance and academic outcomes**.

---

## Features

* Predict student exam scores using Machine Learning
* Interactive **Streamlit web interface**
* Simple and user-friendly input controls
* Real-time score prediction
* Data validation to keep results within valid score range (0–100)
* Educational performance analysis based on lifestyle and study habits

---

## Technologies Used

* Python
* Streamlit
* NumPy
* Scikit-learn
* Joblib

---

## Project Structure

```
Student-Exam-Result-Prediction
│
├── app.py
├── train_model.py
├── best_model.pkl
├── dataset.csv
└── README.md
```

### File Description

* **app.py** → Streamlit web application for exam score prediction
* **train_model.py** → Script used to train the machine learning model
* **best_model.pkl** → Saved trained machine learning model
* **dataset.csv** → Dataset used to train the model
* **README.md** → Project documentation

---

## Dataset Features

The model predicts exam scores based on the following features:

* **Study Hours Per Day** – Average number of hours spent studying
* **Attendance Percentage** – Student attendance rate in class
* **Mental Health Rating** – Student mental wellness level (1–10 scale)
* **Sleep Hours Per Night** – Average sleep duration
* **Part-Time Job** – Whether the student has a part-time job (Yes/No)

### Target Variable

* **Exam Score (0 – 100)**

---

## Install Required Libraries

```
pip install streamlit numpy scikit-learn joblib

```

## Train the Model

Run the model training script before starting the application.

```
python train_model.py
```

This will generate the trained model file:

```
best_model.pkl
```

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

1. The user enters student information in the web interface.
2. The data is processed and converted into a numerical format.
3. The trained machine learning model predicts the exam score.
4. The predicted score is displayed to the user.

---

## Example Input

| Feature       | Example |
| ------------- | ------- |
| Study Hours   | 4       |
| Attendance    | 85      |
| Mental Health | 7       |
| Sleep Hours   | 7       |
| Part-time Job | No      |

### Output Example

```
Predicted Exam Score: 82.45
```

---

## Future Improvements

* Add more student-related features
* Improve model accuracy using advanced algorithms
* Add performance visualization dashboards
* Deploy the project online using **Streamlit Cloud**
* Integrate with school data systems

---