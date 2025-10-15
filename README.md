Diabetes Prediction using Machine Learning
This project aims to predict the likelihood of diabetes in patients based on various diagnostic measurements. It utilizes machine learning models, specifically K-Nearest Neighbors (KNN) and Gaussian Naive Bayes, to classify individuals as likely to have diabetes or not.

Dataset
The dataset used in this project is the "Pima Indians Diabetes Database". It contains health metrics for female patients of Pima Indian heritage. The dataset includes the following columns:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 if not diabetic, 1 if diabetic)
Project Structure
The project is structured as a Jupyter Notebook (or Google Colab notebook) which includes the following steps:

Import Libraries: Import necessary Python libraries for data manipulation, machine learning, and visualization.
Load Dataset: Load the diabetes dataset into a pandas DataFrame.
Data Exploration: Display column names and potentially perform basic data exploration (not explicitly shown in the provided notebook, but recommended).
Define Features and Target: Separate the dataset into features (input variables) and the target variable (Outcome).
Split Data: Split the dataset into training and testing sets to evaluate the performance of the models.
Initialize Models: Initialize the chosen machine learning models (KNN and Gaussian Naive Bayes).
Train Models: Train both models using the training data.
Make Predictions: Make predictions on the test set using the trained models.
Evaluate Models: Evaluate the performance of the models using metrics such as the classification report.
How to Run the Notebook
Clone the repository to your local machine or open it in Google Colab.
Ensure you have the necessary libraries installed (pandas, numpy, scikit-learn, matplotlib). You can install them using pip:
