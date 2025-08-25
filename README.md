# 🚢 Titanic Survival Prediction: A Production-Ready ML Pipeline

## 🎯 Project Overview
This project demonstrates my end-to-end capability to solve binary classification problems through a complete machine learning workflow. Using the classic **Kaggle Titanic dataset**, I developed a high-performance predictive system that determines passenger survival likelihood with **83% cross-validated accuracy** by leveraging sophisticated feature engineering and systematic model optimization.

**Dataset Source:** [Kaggle: Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **`train.csv`**: Labeled training data (891 passengers)
- **`test.csv`**: Unseen test data for prediction (418 passengers)

## 🏆 Technical Highlights

### 🔍 Advanced Feature Engineering
I transformed raw passenger data into powerful predictive signals through:
- **Social Title Extraction**: Engineered `Title` feature from passenger names, identifying nobility, military status, and marital status
- **Family Dynamics Analysis**: Created `Family_Size` and `Family_Size_Grouped` features capturing survival patterns across family structures
- **Ticket Intelligence**: Developed `TicketNumberCounts` to identify group travel patterns and survival advantages
- **Cabin Presence Detection**: Implemented `Cabin_Assigned` binary feature that **doubled predictive power** for passenger class distinction
- **Optimal Binning**: Converted `Age` and `Fare` into ordinal categories based on survival-rate optimized thresholds
- **Name Length Analysis**: Created `Name_Size` feature capturing socioeconomic status through name complexity

### ⚙️ Robust Preprocessing Pipeline
I built a production-grade data processing system using:
- **Custom ColumnTransformer** with specialized handling for different data types
- **Stratified Data Splitting** ensuring representative training/validation sets
- **Automated Missing Value Imputation** using column-specific strategies
- **Dual Encoding Strategy**: Ordinal encoding for engineered features, One-Hot encoding for categorical variables
- **Pipeline Architecture**: Modular design ensuring reproducible preprocessing and avoiding data leakage

### 🧠 Systematic Model Development
I implemented a comprehensive model selection framework:
- **6 Algorithm Benchmarking**: Random Forest, Decision Tree, K-NN, SVM, Logistic Regression, GaussianNB
- **Hyperparameter Optimization** via GridSearchCV with 5-fold stratified cross-validation
- **Performance-Driven Selection**: Random Forest emerged as optimal model (83% accuracy)
- **Prevention of Overfitting** through rigorous cross-validation and parameter tuning
- **Model Interpretability**: Analysis of feature importance and decision boundaries for business insights

## 📊 Key Results & Impact
- **Achieved 83% Cross-Validated Accuracy** with Random Forest classifier
- **Identified Critical Survival Factors**: Cabin assignment, passenger class, and family size emerged as top predictors
- **Delivered Actionable Insights**: Survival rate analysis revealed 2.2x higher survival for passengers with cabin assignments
- **Production-Ready Pipeline**: Built scalable workflow suitable for deployment with new passenger data

## 🛠️ Technical Stack
**Machine Learning & Modeling:** Scikit-learn  
**Data Processing & Analysis:** Pandas, NumPy  
**Data Visualization:** Matplotlib, Seaborn  
**Development & Experimentation:** Jupyter

## 💡 Value Delivered
This project demonstrates my ability to transform raw data into business-ready ML solutions, combining technical expertise in feature engineering with practical model deployment skills. The systematic approach ensures reproducible results while the focus on interpretability provides actionable insights for decision-making.
