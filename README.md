# 🚢 Titanic Survival Prediction: A Production-Ready ML Pipeline

## 🎯 Project Overview
This project demonstrates my end-to-end capability to solve binary classification problems through a complete machine learning workflow. I developed a high-performance predictive system that determines passenger survival likelihood on the Titanic with **83% cross-validated accuracy** by leveraging sophisticated feature engineering and systematic model optimization.

## 🏆 Technical Highlights

### 🔍 Advanced Feature Engineering
I transformed raw passenger data into powerful predictive signals through:
- **Social Title Extraction**: Engineered `Title` feature from passenger names, identifying nobility, military status, and marital status
- **Family Dynamics Analysis**: Created `Family_Size` and `Family_Size_Grouped` features capturing survival patterns across family structures
- **Ticket Intelligence**: Developed `TicketNumberCounts` to identify group travel patterns and survival advantages
- **Cabin Presence Detection**: Implemented `Cabin_Assigned` binary feature that **doubled predictive power** for passenger class distinction
- **Optimal Binning**: Converted `Age` and `Fare` into ordinal categories based on survival-rate optimized thresholds

### ⚙️ Robust Preprocessing Pipeline
I built a production-grade data processing system using:
- **Custom ColumnTransformer** with specialized handling for different data types
- **Stratified Data Splitting** ensuring representative training/validation sets
- **Automated Missing Value Imputation** using column-specific strategies
- **Dual Encoding Strategy**: Ordinal encoding for engineered features, One-Hot encoding for categorical variables

### 🧠 Systematic Model Development
I implemented a comprehensive model selection framework:
- **6 Algorithm Benchmarking**: Random Forest, Decision Tree, K-NN, SVM, Logistic Regression, GaussianNB
- **Hyperparameter Optimization** via GridSearchCV with 5-fold stratified cross-validation
- **Performance-Driven Selection**: Random Forest emerged as optimal model (83% accuracy)
- **Prevention of Overfitting** through rigorous cross-validation and parameter tuning

## 🛠️ Technical Architecture

### Core Technologies
```python
# Machine Learning Framework
scikit-learn = "1.2+"

# Data Processing
pandas = "1.5+"
numpy = "1.23+"

# Visualization
matplotlib = "3.7+"
seaborn = "0.12+"

# Development Environment
jupyter = "1.0+"
