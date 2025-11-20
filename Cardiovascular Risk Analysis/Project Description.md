**Class_Cardiovascular_Risk – Machine Learning Classification Project**

**Dataset Overview**

The dataset includes key health and lifestyle indicators such as:
Age
Gender
Height & Weight
BMI
Blood Pressure (Systolic / Diastolic)
Cholesterol levels
Glucose levels
Smoking habits
Alcohol consumption
Physical activity

These features are used to predict the target variable indicating cardiovascular risk (0 = No Risk, 1 = Risk).


**Project Workflow**
1. Data Loading & Initial Analysis
Inspected dataset structure and attributes
Checked missing values, data types, and summary statistics

2. Data Cleaning & Preprocessing
Replaced inconsistent values and handled missing data
Normalized numeric features
Encoded categorical variables
Identified and treated outliers using IQR

3. Exploratory Data Analysis (EDA)
Created histograms, boxplots, count plots, and bar charts
Visualized lifestyle factors (smoking, alcohol, activity)
Generated a correlation heatmap to identify key relationships
Examined feature distributions between risk vs. no-risk groups

4. Model Building
Applied multiple classification algorithms, such as:
Logistic Regression
Random Forest Classifier
Decision Tree
XGBoost (optional)
Performed:
Train–test splitting
Model training
Hyperparameter tuning (if implemented)

5. Model Evaluation
Evaluated models using:
Accuracy
Precision, Recall, F1-score
Confusion matrix
ROC-AUC score
Selected the best-performing model for final predictions.


**Key Insights**

Lifestyle patterns (smoking, alcohol, low activity) strongly correlate with cardiovascular risk
Higher glucose, cholesterol, and blood pressure significantly increase risk
Age and BMI show clear upward trends in high-risk groups


**Tech Stack**
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn


**Usage**
Clone the repository
Install required dependencies
Open the notebook and run all cells to reproduce results
