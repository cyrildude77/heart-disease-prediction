This project implements a diabetes prediction model using machine learning algorithms to analyze and predict the likelihood of diabetes based on patient data. The project is designed to handle large datasets and offers features like data preprocessing, class imbalance handling, multiple model evaluation, and hyperparameter tuning.

Features

Data Preprocessing:

Handles missing values by imputing median values.

Scales features using StandardScaler.

Exploratory Data Analysis (EDA):

Visualizes feature distributions, correlations, and outliers.

Class Imbalance Handling:

Balances the dataset using the SMOTE algorithm.

Model Evaluation:

Trains and evaluates Logistic Regression, Random Forest, and XGBoost.

Includes accuracy, ROC-AUC scores, confusion matrix, and PR curve evaluations.

Hyperparameter Tuning:

Optimizes XGBoost parameters using GridSearchCV.

Model Serialization:

Saves the best-trained model for deployment using joblib.

Prerequisites

Python Version:

Python 3.8 or higher

Required Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

imbalanced-learn

xgboost

joblib
