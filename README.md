# CODSOFT-1
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


