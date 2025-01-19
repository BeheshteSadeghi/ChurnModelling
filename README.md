# Churn Modelling

### This project aims to train the best model for predicting customer churn.

### In this project; first, data is studied and several diagrams are depicted for storytelling. Since we face with unbalanced data, categorical data, outliers, unscaled data and exess of features, related packages from python is utilized to prepare data for modelling. 
### In the next step, Pycaret Classification is applied over the cleaned data, and top 5 models are picked for further investigation, which are :

#### 1. CatBoost
#### 2. GradientBoosting
#### 3. AdaBoost
#### 4. RandomForest
#### 5. ExtraTrees

### Then, the hyper-parametes of each model is tuned using the information from Pycaret tool. After that, tuned models are compared using f1-score metric.
### The comparison leads to choosing the Gradient Boosting Classifier as the best model for this dataset.
