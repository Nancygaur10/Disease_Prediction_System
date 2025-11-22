# Disease Prediction System

A **Machine Learning–based web application** built with **Django** that predicts possible diseases based on user-provided symptoms.
The application uses a trained **GradientBoosting Classifier** to analyze symptoms and provide prediction results along with a saved medical history.

## 🧠 Project Overview

The **Disease Prediction System** allows users to select or enter symptoms, submit them, and instantly get a predicted disease based on trained machine-learning logic.
The system also maintains a **medical history** table, which stores past user inputs and prediction results.

## 🚀 Features

✅ 1. About Section

A clean informational section explaining the purpose of the system.

✅ 2. Disease Prediction Page

-  User fills a form containing symptoms

-  Model predicts the disease using GradientBoosting Classifier

-  Displays prediction result clearly

✅ 3. Medical History Section

-  Stores and displays previous predictions

-  Pagination / table display

-  Shows symptom values and prediction results


## 🛠 Tech Stack

-   **Django:** 5.2.6\
-   **Python:** 3.13.3\
-   **ML Model:** GradientBoostingClassifier\
-   **Frontend:** HTML, CSS, Bootstrap\
-   **Database:** SQLite3

## 📦 Installation & Setup
Follow the steps below to run the project on your system.

### 1. Clone the Repository

    git clone https://github.com/your-username/your-repo.git
    cd your-repo

### 2. Run Server

    python manage.py runserver

Visit:

    http://127.0.0.1:8000/

## 🤖 Machine Learning Model

This project includes a trained **Gradient Boosting Classifier**, which was trained on a dataset of symptoms and diseases.
The ML model file is loaded inside Django views and predicts output based on user symptoms.

## 📁 Project Structure

/project
│── manage.py
│── db.sqlite3
│── /templates
│     ├── index.html
│     ├── parent.html
│     ├── prediction_result.html
│     ├── prediction.html
│     ├── history.html
│── /static
│     ├── /css
│     ├     ├── style2.css
│     ├── /images
│     ├     ├── img.jpg
│── /my_app
│     ├── views.py
│     ├── models.py
│     ├── best_model.pkl
│     ├── label_encoder.pkl
