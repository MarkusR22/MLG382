## About

**MLG382** is designed to forecast students' academic outcomes using historical performance data. By identifying at-risk students early, the tool allows educators to implement timely interventions.

---

## Features

- 📊 **Exploratory Data Analysis** – Visualize distributions, correlations, and trends.
- 🧠 **ML Models** – Includes classification/regression models (e.g., logistic regression, random forests).
- 🧪 **Validation Pipeline** – Split data, train models, evaluate performance (accuracy, RMSE, F1-score, etc.).
- 🎯 **Prediction Module** – Input new student data to generate performance predictions.
- 🧩 **Modular Design** – Easily swap datasets, models, or evaluation metrics.

---

## 📁 Project Structure

`MLG382/`
  - `data/`  
    Contains raw and preprocessed datasets used for training and testing the models.
  
  - `source/`  
    Core Python scripts for:
    - Data cleaning and feature engineering
    - Model training and evaluation
    - Prediction logic

  - `dash_app/`  
    Dash web application source code, including:
    - UI layout and callbacks
    - Model loading and inference logic
    - Render deployment config

  - `GuidedProject_MLG382_2025.pdf`  
    Full project report including background, methodology, results, and reflection.

  - `MLG382_Team_members.txt`  
    List of team contributors and their responsibilities.

  - `requirements.txt`  
    Python dependencies for running the models and Dash app.

  - `README.md`  
    Project summary and structure (this file).

---

## 🌐 Live Demo

You can access the deployed Dash web application here:

🔗 https://mlg382.onrender.com

The web interface allows you to:
- Upload or input new student data
- View real-time predictions based on trained models
- Interpret results through visualizations and model feedback

> _Note: The app is hosted on [Render](https://render.com), and may take a few seconds to wake up if it’s in free-tier sleep mode._
