# Data-science-practice-projects
This repository contains a collection of data science practice projects I’ve worked on, covering various aspects of machine learning, deep learning, and data analysis.

### Cars24 Price Prediction Project
This notebook predicts car prices using machine learning. The dataset is sourced from Kaggle Datasets - [Used Car Price Data from Cars24 on Kaggle](https://www.kaggle.com/datasets/amanrajput16/used-car-price-data-from-cars24) and contains details like manufacturing year, engine capacity, transmission type, fuel type, and ownership.
#### Workflow:
Exploratory Data Analysis (EDA): Visualized the data to understand patterns and distributions.
Model Training: Trained multiple regression models (like XGBoost) for price prediction.
Explainability: Used SHAP (SHapley Additive exPlanations) to interpret feature importance and model behavior.

### Project Title: RFM-Based Customer Segmentation Analysis

#### Objective:
To segment customers based on their purchasing behavior using the RFM (Recency, Frequency, Monetary) model, enabling data-driven insights for targeted marketing strategies.
#### Approach:
Data Preparation: Cleaned and preprocessed transactional data.
Feature Engineering: Calculated RFM metrics:
Recency (R): Number of days since the customer’s last purchase.
Frequency (F): Total number of transactions made by the customer.
Monetary Value (M): Total amount spent by the customer.
#### RFM Scoring: Assigned scores (Low, Mid, High) for each metric based on value distribution:
Low: Bottom 33% of values.
Mid: Middle 33% of values.
High: Top 33% of values.
#### Customer Segmentation: Combined RFM scores to create distinct customer segments (e.g., High Recency – High Frequency – High Monetary = Top Customers).
#### Outcome:
Generated well-defined customer groups for more effective personalized marketing and retention strategies.
