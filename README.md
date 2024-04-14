# Churn Prediction Model

**Project Overview**

This project develops a churn prediction model to identify customers likely to leave a telecommunications company. The model uses customer data and builds several machine learning classifiers to predict churn. This includes data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

**Data**

The dataset 'WA_Fn-UseC_-Telco-Customer-Churn.csv' is used for this analysis. It 
includes various customer attributes such as demographics, account information, and service details.

**Features**

* **Demographics:** Gender, SeniorCitizen, Partner, Dependents.
* **Account information:** Tenure, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges.
* **Services availed:** Multiple lines, Internet services, Online security, Online backup, Device protection, Tech support, Streaming TV, and Streaming movies.

**Models Evaluated**

* Logistic Regression. 
* Random Forest Classifier
* Gradient Boosting Classifier
* Support Vector Machines
* K-Nearest Neighbors
* XGBoost
* Multi-Layer Perceptron

**Evaluation Metrics**

Models are evaluated based on accuracy, precision, recall, F1 score, ROC-AUC score, and confusion matrices.

**Setup and Installation**

* Python version: 3.x
* Required libraries: pandas, numpy, sklearn, matplotlib, seaborn, xgboost

**Usage**

Run the notebook cells sequentially to load the data, preprocess it, train the models, and evaluate their performance.

**Results**

The model's performance metrics are displayed for each classifier, including error tables and feature importance analysis where applicable.

**Future Works**
Further improvements might include hyperparameter tuning, exploring more complex models, and deploying the model for real-time prediction.

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details.
