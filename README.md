# 🩺 Diabetes Prediction using Machine Learning

## 🔍 Overview
This project explores health-related indicators to classify individuals into three categories:  
- **0:** No Diabetes  
- **1:** Prediabetes  
- **2:** Diabetes  

Various preprocessing steps such as handling imbalanced data (SMOTE, RandomUnderSampler), feature selection (RFE), and outlier removal (Z-score) were applied to improve model performance.

## 📂 Dataset
- **Name:** `diabetes_012_health_indicators_BRFSS2015.csv`
- **Description:** A dataset containing health indicators associated with diabetes classification. 

## 🛠️Technologies Used
- 🐍 **Python**  
- 📊 **Pandas, NumPy** (Data Handling)  
- 🎨 **Seaborn, Matplotlib** (Data Visualization)  
- 🤖 **Scikit-learn** (Machine Learning)  
- ⚖️ **Imbalanced-learn** (SMOTE, RandomUnderSampler)  

## 🚀 Project Steps
### 1️⃣ Data Loading 📥  
- Read and explore the dataset.  
- Identify missing values and compute basic statistics.  

### 2️⃣ Exploratory Data Analysis (EDA) 📊  
- Visualized feature distributions.  
- Checked for class imbalance in target labels.  

### 3️⃣ Data Preprocessing 🔄  
- **Outlier detection & removal** using **Z-score**.  
- **Feature selection** with **Recursive Feature Elimination (RFE)**.  
- **Class balancing** via **SMOTE (oversampling) & RandomUnderSampler (undersampling)**.  

### 4️⃣ Machine Learning Models 🤖  
Tested multiple models to compare their effectiveness:  
✅ **Logistic Regression**  
✅ **Gradient Boosting**  
✅ **Decision Tree**  

### 5️⃣ Results & Insights 📈  
- **Compared model performance** under different preprocessing techniques.  
- Assessed the impact of **feature selection** and **outlier removal** on accuracy.  

📌 **Evaluated using:**  
- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1-score  

## Future Improvements
- Experiment with deep learning models.
- Implement additional feature engineering techniques.
- Deploy the model using a web app.

---
✨ *Created by Halyusa Ard Wahyudi as part of a data science portfolio.* 🚀 

