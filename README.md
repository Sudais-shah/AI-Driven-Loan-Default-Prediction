## **AI-Driven Loan Default Prediction**

**Project Overview**
This project predicts whether a person will default on a loan using machine learning. I built it to improve my data science skills and showcase my ability to clean data, engineer features, and optimize models for high accuracy.

**Challenges Faced**
Data Cleaning & Preprocessing – The dataset had missing values, inconsistent formats, and unnecessary columns. I handled missing data using imputation and removed irrelevant features.
Feature Engineering – The model did not perform well with original features. I created new features like debt-to-income ratio, credit utilization, and loan risk scores, which significantly improved accuracy.
Model Performance – Initial models struggled to predict defaults accurately. I tried different techniques like undersampling, oversampling, and threshold tuning, but feature engineering had the biggest impact.

**Model & Results**
I tested multiple models, including Logistic Regression, Random Forest, and XGBoost. After hyperparameter tuning, XGBoost performed the best with:

Accuracy: ~88%
F1-Score: ~86%
AUC-ROC: ~93%

**Key Learnings**
Feature engineering is crucial for improving model performance.
Handling missing values properly improves data quality.
XGBoost is highly effective for loan default prediction.

**Future Work**
Improve feature engineering for better accuracy.
Explore deep learning models.
Deploy the model as an API for real-world use.
