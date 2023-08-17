# Diabetes Prediction and Risk Assessment using SVM
This repository contains a machine learning project that focuses on predicting diabetes diagnosis and assessing diabetes risk using Support Vector Machines (SVM).

# Overview
The project utilizes a dataset containing medical records of patients, focusing on specific symptoms related to diabetes. Two primary tasks were performed:

Diabetes Classification (SVC): Predicting whether a patient has diabetes based on their symptoms using Support Vector Classification.
Diabetes Risk Assessment (SVR): Estimating a patient's risk score for diabetes using Support Vector Regression. The risk score is a synthetic measure based on the number of symptoms a patient exhibits.
Key Files
diabetes.csv: Dataset containing patient records and their diabetes status.
svm_diabetes.ipynb: Jupyter notebook containing all data preprocessing, analysis, modeling, and evaluation steps.

# Key Findings
The SVC model demonstrated high performance in classifying patients with and without diabetes.
The SVR model was used to predict a synthetic "risk score" with high accuracy, demonstrating the mechanics of SVR, even with a synthetic target.

#Setup and Usage
Clone the repository: git clone <repository-url>
Navigate to the project directory.
Install the necessary libraries: pip install -r requirements.txt
Open the Jupyter notebook: jupyter notebook svm_diabetes.ipynb

# Libraries Used
Pandas
Scikit-learn
Seaborn
Matplotlib
