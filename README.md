# Credit Risk Assessment & Explainable Machine Learning

An end-to-end machine learning project for assessing credit default risk using supervised learning and Explainable AI (XAI).

## Overview

This project builds a machine learning pipeline to predict borrower default risk and explain individual predictions using SHAP.

### Workflow

Data → EDA → Preprocessing → Feature Engineering → Model Training → Evaluation → Threshold Optimization → SHAP Explainability → API Inference

## Key Features

- Exploratory Data Analysis and data preprocessing
- Feature engineering for credit-risk modeling
- Binary classification for default-risk prediction
- Machine learning model comparison
- Probability-based risk prediction
- Decision-threshold optimization
- SHAP-based model explainability
- Individual prediction explanations
- FastAPI-based model inference

## Models

- Logistic Regression
- Random Forest
- XGBoost

## Explainable AI

SHAP (SHapley Additive exPlanations) is used to understand how individual features contribute to model predictions.

The project provides both:
- **Global explanations** — identifying the most influential features overall
- **Local explanations** — understanding why a specific borrower received a particular prediction

## Tech Stack

- **Python**
- **pandas / NumPy**
- **scikit-learn**
- **XGBoost**
- **SHAP**
- **FastAPI**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

## Running the Project

### Clone the repository

```bash
git clone https://github.com/vedantmangla/Credit-Risk-Assessment-Explainable-ML.git
cd Credit-Risk-Assessment-Explainable-ML
