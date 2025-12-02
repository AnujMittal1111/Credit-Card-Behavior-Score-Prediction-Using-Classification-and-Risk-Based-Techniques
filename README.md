# Credit Card Behavior Score Prediction Using Classification and Risk-Based Techniques

This project builds a credit default risk prediction system using machine learning and risk-scoring techniques.  
Using a dataset of over 100,000 financial records, the goal is to identify high-risk customers with high recall and interpretability so financial institutions can reduce default exposure.

## Project Summary

- Trained machine learning models on 100K+ financial records to predict customer default behavior.
- Evaluated Logistic Regression, Random Forest, and XGBoost models.
- Improved recall on high-risk segments by 24 percent using feature engineering and threshold tuning.
- Identified the top 15 percent high-risk customers with 12 percent higher true positives.
- Focused on interpretability, risk scoring, and business insights.

This repository includes the complete analysis notebook, prediction file, and project report.

## Repository Structure

SUBMISSION-23117025.ipynb   : Analysis, model training, evaluation  
submission.csv              : Final model predictions  
Report_23117025.pdf         : Full project report  
README.md                   : Project summary  

## Tech Stack Used

### Languages and Tools
- Python  
- Jupyter Notebook  

### Libraries
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  

### Techniques
- Exploratory Data Analysis  
- Data Cleaning and Feature Engineering  
- Classification Models  
- Risk-Based Scoring  
- Threshold Optimization  
- Cross-Validation  
- Evaluation: AUC, Precision, Recall, Confusion Matrix  

## Model Performance

- XGBoost performed best on high-risk segments.
- Recall improvement of 24 percent for risky customers.
- Better detection of true risky customers using risk scoring.

## Key Insights

- High-risk customers show distinct patterns in spending and repayment.
- Risk-based scoring improves business interpretability.
- Higher recall reduces financial losses by identifying more risky customers.

## How to Run

1. Install required libraries:

   pip install numpy pandas scikit-learn xgboost matplotlib seaborn

2. Open the notebook:

   SUBMISSION-23117025.ipynb

3. Run all cells to reproduce:
   - Preprocessing  
   - Model training  
   - Evaluation  
   - Predictions  

## Documentation

Refer to Report_23117025.pdf for full methodology, results, and business interpretation.

## Author

Anuj Mittal  
IIT Roorkee  

