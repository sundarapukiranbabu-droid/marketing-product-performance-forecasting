# E-Commerce Sales Forecasting Using Multi-Source Data

## Project Overview

This project develops machine learning models for forecasting e-commerce sales using the Multi-Source Data for E-Commerce Sales Prediction dataset from Kaggle.

The study evaluates different machine learning algorithms, preprocessing techniques, feature importance, robustness, and model selection strategies to identify the most effective model for sales forecasting.

## Dataset

Dataset Name:
Multi-Source Data for E-Commerce Sales Prediction

Source:
https://www.kaggle.com/datasets/algozee/multi-source-data-for-e-commerce-sales-prediction

Rows: 100,000

Columns: 18

## Target Variable

sales_amount_gbp

## Task Type

Regression

## Research Questions

RQ1 - Baseline Performance Analysis

RQ2 - Machine Learning Model Comparison

RQ3 - Impact of Data Preprocessing

RQ4 - Feature Importance Analysis

RQ5 - Sensitivity to Evaluation Metrics

RQ6 - Robustness and Generalization Analysis

RQ7 - Final Model Recommendation

## Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

XGBoost

Google Colab

## How to Run

1. Download the dataset from Kaggle.
2. Upload the CSV file into Google Colab.
3. Execute the notebooks in the notebooks folder.
4. Generated tables will be saved as CSV files.
5. Generated figures will be saved as PDF files.

## Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

## Final Recommendation

Gradient Boosting achieved the strongest overall forecasting performance and demonstrated high robustness across different evaluation scenarios. Therefore, Gradient Boosting is recommended as the final model for deployment in e-commerce sales forecasting applications.

