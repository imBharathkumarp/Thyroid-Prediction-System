# 🧠 Thyroid Disease Prediction System

A Flask web application that predicts whether a patient has a thyroid disorder using machine learning.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python) ![Flask](https://img.shields.io/badge/Flask-2.0-lightgrey?style=flat&logo=flask) ![scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.0-orange?style=flat&logo=scikitlearn)

---

## 🚀 Project Demo

🔗 [Coming Soon on Render.com Deployment!]

---

## 📋 Project Overview

This project uses machine learning models trained on thyroid disease datasets to predict if a person is suffering from:
- **Hyperthyroidism**
- **Hypothyroidism**
- **Normal (No Thyroid Issues)**

We trained the model using `RandomForestClassifier` and deployed it using **Flask** and **Gunicorn**!

---

## 📦 Folder Structure


---

## 🛠️ Technologies Used

- Python 3.10
- Flask
- scikit-learn
- pandas
- numpy
- pickle
- Gunicorn (for production)
- Render.com (for deployment)

---

## 📈 Model Building Process

- **Data Cleaning**
- **EDA (Exploratory Data Analysis)**
- **Feature Engineering**
- **Model Training**
- **Hyperparameter Tuning (Grid Search)**
- **Model Serialization (`pickle`)**

---

## 📜 Installation Guide

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/thyroid-prediction-system.git
cd thyroid-prediction-system
```

2. **Create Virtual Environment**
```bash
python -m venv my_env
.\my_env\Scripts\activate   # Windows
# source my_env/bin/activate   # Linux/Mac
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Run Locally**
```bash
python main.py
```

## ⚙️ Deployment Guide (Render.com)

- Push your code to GitHub.
- Create a new Web Service on Render.
- Connect your GitHub repository.
- Build Command:
```bash
pip install -r requirements.txt
```
- Start Command:
```bash
gunicorn main:app
```
---
## ⭐ Show your support
**If you like this project, kindly ⭐ the repo to support me!**
---

