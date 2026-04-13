# titanic-ml-classifier
End-to-end data science project using the Titanic dataset to build a predictive model for passenger survival. Covers data cleaning, visualization, feature engineering, and machine learning model evaluation to uncover survival patterns.
🚢 Titanic Survival Prediction (KNN)
📌 Description

This project aims to predict whether a passenger survived the Titanic disaster using machine learning. It leverages a K-Nearest Neighbors (KNN) classification model trained on selected features from the Titanic dataset.

The project covers key steps of a data science workflow: data preprocessing, feature selection, model training, and prediction.

🎯 Objectives
Predict passenger survival based on key features
Understand the impact of variables such as class, age, and gender
Build and evaluate a machine learning classification model
📊 Dataset

The dataset used is the famous Titanic dataset, containing information about passengers such as:

Survival (target variable)
Passenger class (Pclass)
Sex
Age
⚙️ Technologies Used
Python
Pandas
Seaborn
Scikit-learn
🔍 Data Preprocessing
Selection of relevant features: Survived, Pclass, Sex, Age
Handling missing values by removing incomplete rows
Encoding categorical variable (Sex → male = 0, female = 1)
🤖 Model
Algorithm: K-Nearest Neighbors (KNN)
Training performed using Scikit-learn
Model evaluation using accuracy score
📈 Results

The model is trained and evaluated on the dataset, achieving an accuracy score (on training data).
⚠️ Note: The model is evaluated on the same dataset used for training, which may lead to overfitting.
