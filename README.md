# Intelligent Multi-Modal Weather Intelligence and Climate Decision Support Platform

## Phase 02 – Part 01

This project focuses on the development of an AI-based weather prediction system for analyzing and forecasting rainfall using publicly available meteorological data.

## Objective

The objective is to develop a machine learning-based rainfall prediction system using meteorological variables and temporal features.

## Dataset

The dataset was obtained from NASA POWER.

Location:
Coimbatore, Tamil Nadu, India

Latitude: 11.0168
Longitude: 76.9558

Period:
2010–2025

Variables:

- Temperature at 2 meters
- Dew/Frost Point at 2 meters
- Precipitation
- Wind Speed at 10 meters
- Surface Pressure

## Methodology

The project includes:

1. Data acquisition
2. Data preprocessing
3. Exploratory Data Analysis
4. Correlation analysis
5. Feature engineering
6. Lag feature creation
7. Rolling-window features
8. Rainfall event analysis
9. Random Forest regression
10. XGBoost regression
11. Model comparison
12. Feature importance analysis
13. SHAP explainability
14. Rainfall prediction

## Models

Two machine learning models were evaluated:

- Random Forest
- XGBoost

## Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Random Forest | 2.0822 | 3.5199 | 0.5503 |
| XGBoost | 2.0306 | 3.4628 | 0.5648 |

XGBoost achieved the best performance among the evaluated models.

## Explainability

SHAP was used to analyse feature contributions and improve model interpretability.

The most important features included:

- 7-day rainfall rolling mean
- Previous-day rainfall
- 3-day rainfall lag
- Wind speed
- Dew point temperature

## Future Work

Future development will extend the system with:

- Deep learning models such as LSTM
- Satellite image analysis
- Remote sensing data
- Weather APIs
- RAG-based scientific knowledge retrieval
- AI agents
- Weather intelligence assistant
- FastAPI backend
- Streamlit/Gradio interface

## Technologies

Python  
Pandas  
NumPy  
Matplotlib  
Scikit-learn  
XGBoost  
SHAP  
Google Colab  
GitHub
