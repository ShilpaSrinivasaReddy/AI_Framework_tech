# Hospital Admission Prediction

## Overview

This project aims to predict the length of stay for patients in a hospital based on various features. The dataset includes information such as hospital details, patient demographics, admission type, severity of illness, and more.

## Dataset

The dataset consists of the following columns:

- `case_id`: Case_ID registered in the hospital
- `Hospital_code`: Unique code for the hospital
- `Hospital_type_code`: Unique code for the type of hospital
- `City_Code_Hospital`: City Code of the hospital
- `Hospital_region_code`: Region Code of the hospital
- `Available Extra Rooms in Hospital`: Number of extra rooms available in the hospital
- `Department`: Department overlooking the case
- ...

## Libraries Used

- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- SHAP

## Data Exploration and Preprocessing

The dataset is explored to handle missing values and visualize the distribution of various features. Feature engineering is performed, including one-hot encoding for categorical variables, log transformation for numerical variables, and creating interaction terms.

## Model Selection and Training

Random Forest, Logistic Regression, and Decision Tree models are trained on the dataset after handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## Explainable AI (XAI)

SHAP values are utilized for model interpretability. A TreeExplainer is used for the Random Forest model, and SHAP values are calculated to understand the impact of each feature on the model predictions.

## Model Evaluation and Optimization

RandomizedSearchCV is employed for hyperparameter tuning of Random Forest and Decision Tree models to optimize their performance.

## Usage

- Clone the repository
- Install the required libraries: `pip install -r requirements.txt`
- Run the Jupyter Notebook or Python script

## Contributors
- [Shilpa Srinivasareddy](https://github.com/ShilpaSrinivasaReddy)



