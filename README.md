# CODSOFT Projects
#(Task 1 ) : -
🌸 Iris Flower Classification – Project Report

📌 Project Title:

Iris Flower Classification using Machine Learning
🧠 Objective:

To develop a machine learning model capable of accurately classifying Iris flowers into one of the three species — Setosa, Versicolor, or Virginica — based on four morphological features:

Sepal Length

Sepal Width

Petal Length

Petal Width


📂 Dataset Overview:

Name: Iris Dataset

Source: UCI Machine Learning Repository

Total Instances: 150

Number of Classes: 3

Target Variable: Species

Features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

🧹 Data Preprocessing:

The dataset was loaded and inspected for unnecessary columns.

The 'Id' column was dropped as it did not contribute to classification.

Features (X) and labels (y) were separated.

The dataset was split into training and testing sets using an 80:20 ratio.

🧠 Model Used:

Random Forest Classifier

Number of estimators: 100

Random seed: 42 for reproducibility


This ensemble learning method was chosen for its robustness and high accuracy in handling small datasets like Iris.

✅ Model Performance:

The model achieved 100% accuracy on the test dataset.

All three Iris species were classified correctly.

Evaluation Metrics:

Precision: 1.00 for all classes

Recall: 1.00 for all classes

F1-Score: 1.00 for all classes

Support: 10 (Setosa), 9 (Versicolor), 11 (Virginica)



This confirms the model's perfect performance on the given test data.

💾 Model Deployment:

The trained model was saved using joblib in a file named iris_model.pkl.

This allows for reusing the model in future applications without retraining.

🔍 Key Learnings:

Gained hands-on experience with the complete machine learning pipeline: data loading, cleaning, model building, evaluation, and saving.

Understood the application of Random Forest in multi-class classification problems.

Learned to interpret classification metrics for evaluating model performance.

🚀 Future Enhancements:

Add a graphical interface using Streamlit for real-time predictions.

Perform feature importance analysis to understand which traits are most decisive.

Deploy the model on a cloud platform or as a web app.

#(Task 2)
Project Overview

The dataset used is the classic Titanic Dataset, which includes information about passengers such as age, sex, ticket class, and embarkation port. The goal is to build a predictive model that determines whether a passenger survived the disaster.
🔍 Steps Performed

1. Data Cleaning

Removed unnecessary columns: PassengerId, Name, Ticket, Cabin

Handled missing values in Age (median) and Embarked (mode)



2. Data Preprocessing

Applied Label Encoding to convert categorical variables: Sex and Embarked



3. Model Training

Split the data into training and testing sets (80/20)

Trained a RandomForestClassifier with 100 trees



4. Model Evaluation

Achieved 82.12% accuracy on the test set

Classification report shows:

Precision: 0.83 (class 0), 0.81 (class 1)

Recall: 0.88 (class 0), 0.74 (class 1)

F1-Score: 0.85 (class 0), 0.77 (class 1)


📈 Performance Summary

Metric	Value

Accuracy	82.12%
Macro Avg F1	0.81
Weighted Avg F1	0.82


🛠 Tech Stack

Python

Pandas

Scikit-learn

📁 Files Included

Titanic-Dataset.csv – Dataset used

titanic_model.py or .ipynb – Model training and evaluation code

#(Task 3)
Sales Prediction Using Linear Regression

1. Objective

The primary objective of this project was to develop a linear regression model to predict product sales based on advertising expenditure across three media channels: TV, Radio, and Newspaper.

2. Methodology

Dataset: Utilized a dataset containing advertising budgets (TV, Radio, Newspaper) and corresponding Sales figures.

Preprocessing: Checked for null values and data types; found the dataset clean and ready for modeling.

Modeling: Implemented a LinearRegression model using scikit-learn. The dataset was split into training (80%) and testing (20%) sets.

Evaluation Metrics:

Mean Squared Error (MSE): 2.91

Root Mean Squared Error (RMSE): 1.71

R² Score: 0.91


3. Results & Interpretation

The model achieved an R² score of 0.91, indicating that it explains 91% of the variance in sales.

Coefficients of the model:

TV: 0.0545

Radio: 0.1009

Newspaper: 0.0043



These coefficients suggest that investments in Radio and TV significantly impact sales, while Newspaper has a minimal effect.

Visualization: A scatter plot of actual vs. predicted sales demonstrated that the model performs well, with points closely aligned along the ideal prediction line.


4. Conclusion

The linear regression model provides a strong predictive capability for estimating sales based on advertising budgets. The insights gained can help in optimizing marketing strategy by reallocating budgets toward more effective channels like TV and Radio.




✅ Conclusion

The Random Forest model provided a reliable prediction with over 82% accuracy. This project demonstrates fundamental steps in a classification task: preprocessing, training, and evaluation.


