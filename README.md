# Kaggle-Challenge-18
Spaceship Titanic: Passenger Transport Prediction
Overview
This project aims to predict which passengers were transported to an alternate dimension during the Spaceship Titanic mission. The dataset contains information about passengers, including their demographics, spending habits, and cabin details. Using machine learning models, we analyze and predict the likelihood of each passenger being transported.

Project Structure
Data Loading and Preprocessing:

Load the training and test datasets.
Handle missing values using median imputation for numerical features and mode for categorical features.
Normalize numerical features using StandardScaler.
Feature Engineering:

Create new features such as TotalSpending (sum of various spending columns) and FamilySize (derived from PassengerId).
Apply one-hot encoding to categorical features.
Feature Selection:

Select features for modeling, including engineered features like TotalSpending and FamilySize.
Model Training and Evaluation:

Split the training data into training and validation sets.
Train multiple models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
Evaluate models using accuracy, confusion matrices, and classification reports.
Select the best model based on performance metrics.
Explainable AI (XAI):

Use feature importance to understand the contribution of each feature.
Apply SHAP values to explain individual predictions and overall feature impact.
Plot ROC curve to assess the model's performance.
