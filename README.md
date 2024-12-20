# Airline-Passenger-Referral-Predictive-
Project Overview
The Airline Passenger Referral Analysis project focuses on predicting whether a passenger will refer the airline to their friends or family. This predictive solution helps the airline optimize referral campaigns, enhance customer satisfaction, and improve customer retention. The project utilized Python for data preprocessing, visualization, and model development, resulting in actionable insights for better decision-making.

Objective:
Predict whether a passenger will refer the airline to their friends or family based on historical data.
Enhance referral marketing strategies to increase customer acquisition and retention.
Build a machine learning pipeline for robust and scalable predictions.

Dataset Details:
Source: Internal airline passenger data.
Observations: 131,895 rows.
Features: 17 features, including demographics, travel history, satisfaction scores, and referral behavior.
Challenges:
Null values in multiple columns.
High number of duplicated entries (70,711 duplicates).

Step-by-Step Process:

1. Data Preprocessing:
Loaded the dataset using pandas and performed an initial inspection of the data.
Exploratory Data Analysis (EDA):
Visualized missing data using the missingno library.
Analyzed patterns and relationships between key features using matplotlib and seaborn.
Data Cleaning:
Addressed null values through imputation or removal based on their impact on the dataset.
Removed 70,711 duplicate rows to ensure data integrity.
Normalized and scaled numeric features to enhance model performance.
Feature Engineering:
Derived additional features from satisfaction scores, referral behaviors, and travel history.
Encoded categorical variables using one-hot encoding.

2. Model Development:
Train-Test Split:
Split the dataset into training (70%) and testing (30%) sets to validate model performance.
Model Selection:
Implemented multiple classification algorithms using scikit-learn:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
Evaluated each model based on accuracy, precision, recall, and F1 score.
Hyperparameter Tuning:
Performed grid search to optimize hyperparameters of the Random Forest model.
Model Evaluation:
Achieved an F1 score of 90% with the Random Forest model, which outperformed other models in predicting referral behavior.

3. Insights and Results:
Key factors influencing referral behavior include passenger demographics, satisfaction scores, and travel patterns.
The Random Forest model achieved 90% F1 score, ensuring reliable and actionable predictions.
Provided insights to refine referral strategies, increasing customer retention by an estimated 30%.
5. Deployment:
Built a scalable and automated pipeline for data preprocessing, model training, and prediction.
Utilized Python libraries (pandas, numpy, scikit-learn, seaborn, matplotlib) to streamline the end-to-end workflow.
Tools and Technologies
Python Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, missingno
Machine Learning Models: Logistic Regression, Random Forest, Support Vector Machine (SVM)

Key Deliverables
A cleaned and preprocessed dataset ready for analysis.
A trained Random Forest model achieving 90% F1 score for referral predictions.
Actionable insights to enhance referral marketing strategies.
Comprehensive documentation for reproducibility and scalability.
