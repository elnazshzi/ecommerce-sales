# 🛒 E-Commerce Prediction Project

<img width="1222" alt="Screenshot 2024-11-19 at 00 13 49" src="https://github.com/user-attachments/assets/9a61334f-67e8-4c93-b4fb-7335da4903ff">

## 📈 Problem Statement / Business Objective

In the fast-paced e-commerce industry, predicting transaction amounts is vital for optimizing business strategies and enhancing customer experience. This project develops machine learning models to predict the "Amount" of transactions and identifies key factors driving these predictions. A **Tableau dashboard** supplements the analysis with interactive visualizations for better data-driven decisions.

## 🔍 Data Analysis Workflow

### 1. 📊 Data Collection
The dataset, sourced from **Amazon India**, includes:
- **Style**: Product style.
- **Category**: Product category.
- **Qty**: Quantity of items purchased.
- **Ship Service Level**: Delivery options selected.
- **Fulfillment**: Fulfillment status.
- **Status**: Current transaction state.
- **Ship Postal Code**: Destination postal code.

### 2. 🧹 Data Understanding and Wrangling
- Handled missing values and ensured data consistency.
- Adjusted feature formats for easier analysis.

### 3. 🔍 EDA - Exploratory Data Analysis
- Explored distributions, correlations, and relationships between features.
- Found that **Style** and **Category** strongly influence transaction amounts.

### 4. ⚙️ Model Development
Two models were developed and evaluated:
- **Linear Regression**: Initial baseline for predictions.
- **Random Forest**: Final model with improved accuracy.

### 5. 📉 Feature Importance Analysis
- Conducted permutation-based feature importance analysis.
- Key influential features:
  - **Style** and **Category**: Most impactful.
  - **Qty**: Positively correlated with transaction amounts.

### 6. 🚀 Model Performance
- Compared model metrics:
  - **Linear Regression RMSE**: Higher error.
  - **Random Forest RMSE**: Lower error with better accuracy.
- Random Forest emerged as the better model.

## 📊 Tableau Dashboard

A **Tableau dashboard** accompanies this project, offering:
- Interactive visualizations of feature trends.
- Insights into key drivers of transaction amounts.

<img width="1203" alt="tableau_dashboard" src="https://via.placeholder.com/1203x400">

## 🏆 Results and Insights
- **Random Forest Model:** Provided the most accurate predictions.
- **Key Features Identified:**
  - **Style and Category:** Strong drivers of transaction amounts.
  - **Qty:** Moderate influence.
- **Low-Impact Features:** Status and Ship Postal Code contribute minimally.
