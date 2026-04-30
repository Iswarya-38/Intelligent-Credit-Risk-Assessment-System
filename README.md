# Intelligent Credit Risk Assessment System  

End-to-end machine learning project covering objectives, dataset preparation, feature engineering, modeling, evaluation, and explainability. Built using Python with Logistic Regression and ensemble methods. Demonstrates strong predictive performance with interpretable insights. Future improvements focus on scalability and deployment.

---

## Project Overview  
This project develops an AI-based credit risk assessment system that predicts the probability of loan default, classifies applicants into risk categories, and provides explainable loan decisions to support financial institutions.

---

## Objectives  
- Predict loan default probability  
- Classify applicants into low, medium, and high risk  
- Identify key factors influencing credit risk  
- Improve decision accuracy and efficiency  
- Ensure explainable and transparent predictions  

---

## Dataset and Feature Engineering  
- Dataset: German Credit Dataset  
- Includes financial history, credit score, income, employment, and liabilities  
- Missing values handled  
- Categorical features encoded  
- Feature scaling applied using StandardScaler  
- Derived features:
  - Debt-to-Income Ratio  
  - Loan-to-Income Ratio  
  - Employment stability indicator  

---

## Dataset  
https://www.kaggle.com/datasets/uciml/german-credit  

---

## How to Run  
- Install required libraries (NumPy, Pandas, Scikit-learn, Matplotlib)  
- Load dataset  
- Perform preprocessing and feature scaling  
- Train Logistic Regression and Random Forest models  
- Evaluate using ROC-AUC and classification metrics  
- Generate predictions and risk categories  

---

## Project Workflow  
Data Collection → Preprocessing → Feature Scaling → Feature Engineering → Model Training → Evaluation → Risk Classification → Decision Logic  

---

## Visualizations  
- ROC Curve  
- Confusion Matrix  
- Feature Importance Plot  
- Distribution of Risk Categories  

---

## Technical Stack  
- Python  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## Model Performance  
- ROC-AUC Score: ~0.75–0.85 (varies by model)  
- Improved prediction using Random Forest  
- Balanced performance with cross-validation  
- Reliable classification of risk categories  

---

## Challenges  
- Handling imbalanced dataset  
- Feature correlation and selection  
- Balancing interpretability and performance  

---

## Future Improvements  
- Hyperparameter tuning for better performance  
- Use SHAP for explainability  
- Deploy as web application (Streamlit/Flask)  
- Integrate real-time prediction API  

---

## Key Insights  
- High debt and liabilities increase default risk  
- Stable income reduces risk  
- Ensemble models improve predictive performance  
- Logistic Regression ensures interpretability  

---

## Conclusion  
This system demonstrates how machine learning can enhance credit risk evaluation by providing accurate, explainable, and efficient loan decision support, reducing financial risk while improving operational efficiency.
