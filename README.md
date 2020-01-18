## Detecting Fraud in eCommerce Transactions

(Data: https://www.kaggle.com/c/ieee-fraud-detection/data)

In this project, I predict the probability that an eCommerce transaction is fraudulent. I analyze data, engineer features, and compare several classifiers to select and tune the best model.

The goal is to improve the efficacy of fraudulent transaction alerts, helping businesses reduce their fraud loss and improve customer satisfaction.

Topics:

- Exploratory Data Analysis
- Feature Engineering (including Principal Component Analysis (PCA))
- Class imbalance techniques (Random Undersampling, Synthetic Minority Oversampling Technique (SMOTE))
- Model selection and tuning (Logistic Regression, Decision Tree, Gradient Boosting Classifier, Random Forest Classifier, GridSearchCV)
- Model evaluation (Area under Receiver Operating Characteristics curve (ROC AUC))

# Summary Findings
After analyzing the data and comparing models, I trained a gradient boosting classifier with ROC AUC=0.94. There is a 94% chance that this model will be able to distinguish between fraudulent and normal transactions.
