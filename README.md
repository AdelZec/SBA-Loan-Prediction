# SBA-Loan-Prediction
Built logistic regression and XGBoost models to predict SBA loan default risk using historical loan application data. Performed data cleaning, feature engineering, and class imbalance handling. 

## Models Used
- **Logistic Regression**
- **XGBoost**

## Key Techniques
- Data cleaning and preprocessing of structured financial datasets  
- Feature engineering to identify key drivers of loan default  
- Handling class imbalance to improve detection of high-risk borrowers  
- Model evaluation using **cross-validation, ROC-AUC, precision, recall, and F1-score**

## Results
- Logistic Regression: baseline performance  
- XGBoost: reduced false negatives **~67% improvement** while maintaining high overall accuracy  
- Key features driving loan default: loan amount, borrower credit history, business type, and term length
