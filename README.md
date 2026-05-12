
# Titanic Survival Prediction: Optimized ML Pipeline

## 🚀 Project Overview

This repository implements a robust Machine Learning solution to predict passenger survival on the Titanic. The implementation focuses on **production-ready code** standards, utilizing Scikit-Learn's advanced features to ensure reproducibility and high performance.

## 🛠️ Technical Architecture

- **Pipeline Processing**: Integrated `ColumnTransformer` to handle disparate data types (numerical and categorical) automatically.
- **Feature Engineering**:
  - **Numerical**: Automated imputation of missing values followed by standard scaling.
  - **Categorical**: Strategy-based imputation and One-Hot Encoding for categorical features.
- **Model**: `GradientBoostingClassifier` — selected for its superior performance on tabular datasets.
- **Optimization**: Exhaustive hyperparameter tuning using `GridSearchCV` to find the optimal balance between bias and variance.

## 📊 Key Results

- **Validation Accuracy**: ~81%
- **Best Parameters**: Automated selection of learning rate, tree depth, and estimator count through cross-validation.

## 💻 Installation & Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/Titanic-Survival-Predictor.git](https://github.com/your-username/Titanic-Survival-Predictor.git)
   ```
