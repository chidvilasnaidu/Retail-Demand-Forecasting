# Retail-Demand-Forecasting

## Project Overview

An end-to-end machine learning project designed for forecasting weekly retail sales with Walmart Store Sales data. This project focuses on creating a comprehensive forecasting pipeline capable of generating accurate demand forecasts, and also generating insights that can be acted on from model performance and explainable AI. This project spans the full machine learning project life cycle: data preprocessing, EDA, feature engineering, modeling, hyper-parameter tuning, robustness testing, and explainability (SHAP & LIME).n

---

## Repository Structure

```
Retail-Demand-Forecasting/
│
├── datasets/
│   ├── train.csv
│   ├── test.csv
│   ├── features.csv
│   └── stores.csv
│
├── Retail-Demand-Forecasting.ipynb
├── Model Comparison Report.ipynb
├── Process_Flow_Document.pdf
├── optuna_study.pkl
├── requirements.txt
└── README.md
```

---

## Project Workflow

The project follows the workflow below:

1. Data Ingestion
2. Data Cleaning & Transformation
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Transformation
6. Model Development
7. Hyperparameter Tuning using Optuna
8. Model Evaluation
9. Robustness Testing
10. Model Explainability (LIME & SHAP)
11. Final Model Selection

---

## Machine Learning Models

The following regression models were implemented and evaluated:

- Linear Regression
- Random Forest
- XGBoost

The final model was selected based on validation performance after hyperparameter optimization.

---

## Explainable AI

To improve model transparency and interpretability, the following explainability techniques were implemented:

- **LIME** for local prediction explanations.
- **SHAP** for global feature importance and feature contribution analysis.

---

## Evaluation Metrics

The models were evaluated using:

- Weighted Mean Absolute Error (WMAE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

Since this project is based on the Walmart Store Sales Forecasting problem, **Weighted Mean Absolute Error (WMAE)** was used as the primary optimization metric because holiday prediction errors carry greater business significance.

---

## Installation

Clone the repository and install the required dependencies.

```bash
git clone <repository-url>

cd Retail-Demand-Forecasting

pip install -r requirements.txt
```

---

## Running the Project

For the best understanding of the project, review the files in the following order:

### 1. Retail-Demand-Forecasting.ipynb

Contains the complete implementation including:

- Data preprocessing
- Exploratory data analysis
- Feature engineering
- Model training
- Hyperparameter tuning
- Model evaluation
- Explainable AI

---

### 2. Model Comparison Report.ipynb

Contains:

- Model comparison
- Trade-off analysis
- Business interpretation
- Robustness testing
- Explainability insights
- Final model selection
- Project summary

---

### 3. Process_Flow_Document.pdf

Provides a high-level overview of the complete machine learning pipeline, including:

- Data ingestion
- Data preprocessing
- Feature engineering
- Model training
- Prediction workflow

---

## Reproducing the Results

To reproduce the project:

1. Install the required libraries from **requirements.txt**.
2. Place the Walmart dataset inside the **datasets/** folder.
3. Execute **Retail-Demand-Forecasting.ipynb** from the first cell to the last.
4. Review the analysis and conclusions in **Model Comparison Report.ipynb**.
5. Refer to **Process_Flow_Document.pdf** for the complete pipeline overview.

---

## Final Note

This repository has been organized to provide a clear separation between implementation, analysis, and documentation.

For the best review experience, it is recommended to view  **Retail-Demand-Forecasting.ipynb**, **Model Comparison Report.ipynb** side by side for better understanding 

