# Heart-Stroke-Prediction

# Heart Stroke Prediction
# Overview
This project aims to predict the likelihood of a stroke based on various health-related factors using machine learning algorithms.

# Dataset
The dataset used in this project is "healthcare-dataset-stroke-data.csv", which contains patient details such as age, hypertension, heart disease, glucose levels, BMI, and smoking status.

# Data Preprocessing
Removed unnecessary columns (id).

Handled missing values in the bmi column by replacing them with the most frequent value.

Converted categorical features into numerical representations.

# Exploratory Data Analysis (EDA)
Performed correlation analysis and heatmap visualization.

Examined stroke dependencies on features such as hypertension, heart disease, and smoking status.

# Model Training
Implemented and evaluated multiple machine learning models:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree Classifier

K-Nearest Neighbors (KNN)

# Model Evaluation
Used various evaluation metrics:

Accuracy Score

F1 Score

Mean Absolute Error

Mean Squared Error

Log Loss

# Conclusion
Logistic Regression, SVM, and KNN achieved similar accuracy (~93.8%), making them reliable choices.

Decision Tree had slightly lower accuracy (~91.8%) but still performs well.

Further investigation is needed into unexpected dependencies, such as higher stroke chances in non-smokers.
