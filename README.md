# Diabetes Prediction with Machine Learning

This project implements a comprehensive machine learning pipeline to predict diabetes from clinical data. The solution includes data cleaning, exploratory analysis, 
feature engineering, and evaluation of multiple classification models to identify the best-performing approach.

# Key Features
- Data Preprocessing: Handles missing values, outliers, and inconsistent categorical data
- Exploratory Analysis: Visualisations for distributions, correlations, and outlier detection
- Feature Engineering: Onehot Encoding and feature-scaling
- Model Comparison: classification algorithms evaluated
- Performance Metrics: Accuracy, F1-score, and confusion matrices

## Models Evaluated
1. Logistic Regression
2. K-Nearest Neighbors
3. Decision Tree
4. SVM (RBF Kernel)
5. Neural Network (MLP)
6. Random Forest
7. Gradient Boosting

#Technical Approach
1. Cleaned and normalised the dataset (1009 samples, 14 features)
2. Performed comprehensive EDA with visualisations
3. Engineered features and scaled data using StandardScaler
4. Trained and evaluated models with stratified 70-30 split
5. Identified best-performing model based on accuracy and F1-score

# Requirements
`pandas` | `numpy` | `seaborn` | `matplotlib` | `scikit-learn`

Simply run the script with `diabetes_unclean.csv` in the same directory to reproduce results.