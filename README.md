# Master Thesis: Bank Fraud Prediction with Machine Learning

## Abstract
Machine learning is the main approach to financial fraud detection. Fraud datasets, however, typically bring several challenges, including a high class imbalance, problematic
model evaluation, and limited interpretability. The novel Bank Account Fraud dataset examined in this thesis is no different. This thesis empirically examines Random Over-
sampling, Synthetic Minority Oversampling (SMOTE), Random Undersampling, and Cost-sensitive Learning as possible solutions to the high-imbalance problem training four
machine learning classification algorithms in the process. Our results show Random Undersampling as the best-performing imbalance-handling technique and Logistic Regression
together with Extreme Gradient Boosting Classifier as the best-performing model in terms of a proposed evaluation metric. Lastly, SHapley Additive exPlanations (SHAP)
and Local Interpretable Model-agnostic Explanations (LIME) frameworks are discussedas a possible solution to explaining black-box models.

## Contents of this repository
* **BaselineModels**: Contains code for hyperparameter tuning of logistic regression, decision tree, random forest, and XGBoost via Randomized Search. Also contains final model training, evaluation and XAI.  
* **ResampledModels**: Similar to BaselineModels, however contains three extra searches with random undersampling, random oversampling and SMOTE.
* **Other**: Contains code used for data cleaning and plotting selected figures.
* **Thesis**: Contains the thesis paper. 
