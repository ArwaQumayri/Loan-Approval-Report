# Loan Approval Prediction  
Machine Learning Classification Model (Random Forest)

## Overview  
This project predicts whether a loan application will be approved based on applicant demographics and loan-related features. The workflow includes data exploration, preprocessing, model training, and performance evaluation. A Random Forest classifier was selected for its strong performance with structured data.

## Dataset  
The dataset includes key attributes such as:  
- Age, gender, education  
- Income and employment experience  
- Home ownership  
- Loan amount, purpose, and interest rate  
- Loan status (target variable)

## Methodology  
- Data cleaning and preprocessing  
- Encoding categorical variables  
- Splitting data into training and testing sets  
- Training a Random Forest classifier  
- Evaluating performance using accuracy, precision, recall, F1-score, ROC curve, and AUC  

## Results  
The model demonstrated strong predictive performance and highlighted important factors influencing loan approval, including income, loan amount, and interest rate.

## Repository Contents  
- **LoanApprovalPredictionReport.pdf** — Full project report  
- **Loan_Approval_Model.ipynb** — Notebook containing all code steps  

## How to Run  
1. Download the notebook  
2. Open it in Google Colab, Jupyter Notebook, or VS Code  
3. Install required libraries:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
