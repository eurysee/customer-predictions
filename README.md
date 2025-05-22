# VIP Customer Prediction

This repository contains a comprehensive machine learning pipeline to predict whether a customer will accept a marketing offer based on their profile and behavior. 
The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, class balancing, and training multiple models to evaluate their predictive performance.


## Dataset

The [Superstore Marketing Campaign Dataset](https://www.kaggle.com/datasets/ahsan81/superstore-marketing-campaign-dataset) from Kaggle includes customer demographics, purchasing behavior, and past marketing campaign responses. 
The dataset is used to classify customers based on their likelihood of accepting an offer.


## Key Features of the Project

- **Data Cleaning**: Handling missing values, correcting inconsistencies, and transforming date features.
- **EDA**: Visualizations and statistical summaries to understand the distribution and relationships in the data.
- **Feature Engineering**: Creation of new features (e.g., `Enrollment_Duration`) and standardization of categorical variables.
- **Outlier Detection**: IQR-based removal of outliers.
- **Class Balancing**: Using SMOTE to handle class imbalance in the target variable.
- **Scaling**: Standardizing features with `StandardScaler`.
- **Model Training**:
  - Logistic Regression
  - Gaussian Naive Bayes
  - K-Nearest Neighbors
  - Decision Tree
  - Random Forest
  - Extra Trees
  - AdaBoost
  - Gradient Boosting
  - Multi-layer Perceptron (Neural Network)
- **Evaluation**: Metrics include Precision, Recall, F1 Score, ROC AUC, and confusion matrix visualization.


## Results
The models are evaluated on two preprocessed versions of the dataset. 
Metrics like F1 score and ROC AUC are compared to select the best-performing model for predicting customer response.

## Notes  
This repository was created as part of a group project for a university Business Intelligence course.
The goal is to analyze customer data and predict the likelihood of a customer responding positively to a marketing campaign.
