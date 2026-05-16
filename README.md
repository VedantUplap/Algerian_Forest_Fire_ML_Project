# Algerian Forest Fire Prediction Using Machine Learning

## Project Overview

This project is an end-to-end Machine Learning web application developed using Flask.  
The model predicts the **Fire Weather Index (FWI)** based on environmental and weather-related input features from the Algerian Forest Fires dataset.

The application takes user input through a web interface and predicts the FWI value using a trained Ridge Regression model.

---

## Problem Statement

Forest fires are one of the major environmental threats affecting ecosystems and human life.  
The goal of this project is to predict the **Fire Weather Index (FWI)** using meteorological data so that fire risk can be analyzed efficiently.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML

---

## Machine Learning Workflow

The project follows a complete machine learning pipeline:

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Data Standardization
6. Model Training
7. Model Evaluation
8. Model Deployment using Flask

---

## Models Compared

The following regression algorithms were trained and evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

The final model selected was:

## Ridge Regression

because it provided the best performance based on the R² Score.

---

## Input Features

The model predicts FWI using the following input parameters:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC
- DMC
- DC
- ISI
- BUI
- Classes
- Region

---

## Project Structure

```text
Algerian-Forest-Fire-Prediction/
│
├── application.py
├── README.md
├── requirements.txt
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates/
│   └── home.html
│
└── notebooks/
    └── model_training.ipynb
```

---

## Flask Application

The Flask web application allows users to:

- Enter environmental parameters
- Submit the form
- Receive predicted FWI values instantly

---

## Model Deployment

The trained Ridge Regression model was serialized using `pickle` and integrated into a Flask application for real-time prediction.

---

## How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/Algerian-Forest-Fire-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Application

```bash
python application.py
```

---

## Output

The application predicts the Fire Weather Index (FWI) based on the provided weather conditions.

---
## Author

Vedant Uplap
BTech CSE Student | AI/ML Enthusiast
