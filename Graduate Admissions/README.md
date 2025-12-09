# Dataset - Graduate Admissions Prediction (Indian Perspective)

This repository contains a curated dataset created for predicting Graduate Admissions from an Indian student perspective.
It is designed for machine learning beginners and enthusiasts to build regression models, evaluate feature importance, and experiment with end-to-end ML workflows.

**Dataset Description**
The dataset includes the following columns:
GRE Score (out of 340)
TOEFL Score (out of 120)
University Rating (1–5)
SOP Strength (1–5)
LOR Strength (1–5)
Undergraduate GPA (out of 10)
Research Experience (0 or 1)
Chance of Admit (target variable)

**Repo Structure**
├── data/
│   └── admissions_india.csv
│
├── eda/
│   └── admissions_eda.ipynb
│
├── models/
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   ├── xgboost.pkl
│   └── scaler.pkl
│
├── src/
│   ├── train_models.py
│   ├── preprocess.py
│   └── predict.py
│
├── notebooks/
│   └── model_comparison.ipynb
│
├── README.md
└── requirements.txt
