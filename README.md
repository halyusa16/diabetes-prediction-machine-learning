# Diabetes Prediction using Machine Learning

## Overview
This project focuses on predicting diabetes using machine learning techniques. Various preprocessing steps such as handling imbalanced data (SMOTE, RandomUnderSampler), feature selection (RFE), and outlier removal (Z-score) were applied to improve model performance.

## Dataset
- **Name:** `diabetes_012_health_indicators_BRFSS2015.csv`
- **Description:** Contains health indicators related to diabetes classification (0: No Diabetes, 1: Prediabetes, 2: Diabetes).

## Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE, RandomUnderSampler)

## Project Steps
1. **Data Loading**
   - Read and explore the dataset.
   - Identify missing values and basic statistics.

2. **Exploratory Data Analysis (EDA)**
   - Feature distribution visualization.
   - Class imbalance check.

3. **Data Preprocessing**
   - Outlier detection and removal using Z-score.
   - Feature selection using Recursive Feature Elimination (RFE).
   - Oversampling (SMOTE) and Undersampling (RandomUnderSampler) to handle class imbalance.

4. **Machine Learning Models**
   - Logistic Regression
   - Gradient Boosting
   - Decision Tree
   - Performance evaluation using accuracy, precision, recall, and F1-score.

5. **Results & Insights**
   - Comparison of models with different data handling techniques.
   - Effectiveness of feature selection and outlier removal.

## Future Improvements
- Experiment with deep learning models.
- Implement additional feature engineering techniques.
- Deploy the model using a web app.

---
*This project was created by Halyusa Ard Wahyudi as part of a data science portfolio.*

