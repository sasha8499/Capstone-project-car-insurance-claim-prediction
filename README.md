# Capstone-project-car-insurance-claim-prediction

Leveraging Data Analytics for Car Insurance Claim Prediction

Problem Statement: Car insurance companies face financial risks when customers make insurance claims within a short duration. Identifying such customers beforehand can help companies to take preventive measures and minimize losses. To address this, predictive model using machine learning techniques in python is built, which can forecast whether a customer is going to claim insurance within short period (six months) or not.

Description: Dataset contains 58,592 rows and 44 columns. It is a binary classification problem where target variable is imbalanced with 94% of class ‘0’ and 6% of class ‘1’. SMOTE technique is utilized to overcome the impact of class imbalance. Thorough EDA has been done along with statistical tests to identify significant features. Several algorithms have been fitted to get the best results and ensembling is applied to improve the performance of model.

Outcome: The model built using XGBoost ensembling obtained 0.93 f1-score, 0.91 recall-score and 0.94 accuracy.

Technologies: Python, EDA, Feature Engineering, Statistical tests, SMOTE, Logistic Regression, Decision tree, Random forest, Ensemble methods.
