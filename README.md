Description:

This project demonstrates how to build a full-featured machine learning pipeline for predicting survival on the Titanic using data preprocessing, feature engineering, and hyperparameter-tuned classification models.

The system is capable of:

Extracting and engineering meaningful features from raw passenger data, including name titles, ticket patterns, and cabin assignments.

Handling missing data and categorical variables using pipelines with encoders and imputers.

Training and tuning multiple classifiers (Random Forest, Decision Tree, KNN, SVC, Logistic Regression, GaussianNB) using GridSearchCV and Stratified K-Folds.

Generating predictions and preparing submission files in the standard Kaggle competition format.

Key Features:

Feature Engineering: Extracts titles from names, ticket prefixes, and cabin indicators to capture socioeconomic status and travel class.

Imputation & Encoding: Handles missing data through column-specific imputers and applies both one-hot and ordinal encoding where appropriate.

Model Selection: Implements and tunes six different classification algorithms using grid search and cross-validation.

Pipeline Integration: Uses ColumnTransformer and Pipeline from scikit-learn for clean, modular, and repeatable preprocessing and model training.

Software:

Python: The main programming language used for data analysis and modeling.

scikit-learn: Provides the machine learning models, transformers, encoders, and tools for pipeline construction and evaluation.

pandas: Used for data manipulation, feature extraction, and preparation.

NumPy: Supports numerical operations and array transformations.

Seaborn & Matplotlib: Used for visualizing distributions, correlations, and exploratory data analysis.

Jupyter Notebook: Serves as the development and experimentation environment for interactive coding.

Libraries:

pandas: For data manipulation and cleaning.

NumPy: For numerical operations and array handling.

Matplotlib & Seaborn: For visualizing feature distributions and survival trends.

scikit-learn: For preprocessing, pipeline design, model tuning, and evaluation.

