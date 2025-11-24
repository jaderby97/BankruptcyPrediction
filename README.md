# BankruptcyPrediction
This project builds and compares **machine learning models to predict corporate bankruptcy** based on financial indicators.  
It focuses on identifying which features are most predictive of bankruptcy risk and evaluating the performance of different modeling approaches.

## Project Overview
The goal was to analyze company financial data to classify firms as “bankrupt” or “healthy” using a combination of interpretable and high-performance models.  
Two main algorithms were compared: **Logistic Regression** (for interpretability) and **XGBoost** (for predictive power).

Key steps included:
- Cleaning and standardizing financial ratio data  
- Performing exploratory data analysis (EDA) to identify patterns and correlations  
- Building and tuning Logistic Regression and XGBoost models  
- Comparing model accuracy, precision, recall, and ROC-AUC  
- Interpreting feature importance to identify key bankruptcy indicators  

## Results & Insights
- Both models achieved strong accuracy, with XGBoost outperforming Logistic Regression on recall.  
- Financial ratios related to liquidity, profitability, and leverage were the strongest predictors.  
- The project highlights the trade-off between **interpretability** and **performance** in financial modeling.

## Tools & Libraries
- Python  
- pandas, numpy  
- scikit-learn, XGBoost  
- matplotlib, seaborn  

## Skills Demonstrated
- Predictive modeling and evaluation  
- Feature selection and importance analysis  
- Data preprocessing for structured financial data  
- Comparative model analysis  
- Business interpretation of model outputs  

## Repository Structure
- `Bankruptcy Prediction.ipynb` – main analysis notebook  
- `american_bankruptcy.csv` – dataset file   
- `README.md` – project overview and documentation
