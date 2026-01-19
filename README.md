# 🧠 Binary Classification Solution – End-to-End ML Pipeline
## 📌 Overview

This repository contains an end-to-end machine learning solution for a binary classification problem, developed as part of a data science competition.

The notebook walks through the complete workflow:

+ Data loading and preprocessing

+ Feature handling

+ Model training and evaluation

+ Hyperparameter tuning

+ Final model selection

The primary focus is on tree-based ensemble methods, with XGBoost emerging as the best-performing model.

## 📊 Problem Description

The task is a binary classification problem where the goal is to predict a target variable with two possible outcomes based on a set of input features.

Performance is evaluated using classification metrics, with particular attention to:

+ ROC-AUC

## 🔄 Workflow Summary
### 1️⃣ Data Preparation

+ Dataset is loaded directly into the notebook

+ Basic inspection and cleaning are performed

+ Features and target variable are separated

+ Data is prepared for model training

### 2️⃣ Models Explored

The following models were implemented and compared:

+ Random Forest Classifier

+ XGBoost Classifier

Each model was evaluated using consistent validation strategies to ensure fair comparison.

### 3️⃣ Model Training & Evaluation

+ Models are trained using carefully chosen parameters

+ Performance is evaluated on validation data

+ XGBoost consistently outperforms Random Forest

Key observations:

+ XGBoost shows stronger generalization

+ Hyperparameter tuning significantly improves results

### 4️⃣ Hyperparameter Tuning

For XGBoost, multiple parameters were adjusted, including:

+ Learning rate

+ Number of estimators

+ Tree depth

+ Subsampling parameters

⚠️ Parameter tuning was guided by the [official XGBoost documentation](https://xgboost.readthedocs.io/en/stable/parameter.html) to ensure best practices and model stability.

## 🏆 Final Model

+ Best Model: XGBoost Classifier

+ Reason: Superior validation performance compared to Random Forest

+ The final tuned model appears at the bottom of the notebook, clearly 
 separated from earlier experiments.


 ## 🚀 How to Run the Notebook

 ### Requirements
 
Install the required Python packages: <br>
```pip install numpy pandas scikit-learn xgboost matplotlib```

### Execution

1. Open codes.ipynb

2. Run cells sequentially from top to bottom

3. Review results and final model at the end of the notebook

## 📈 Results

+ XGBoost achieves the best overall performance

+ Clear improvement over baseline models

+ Stable results across experiments

(Detailed metrics and outputs are shown directly in the notebook.)

## 📝 Notes

+ The notebook contains all experiments, including intermediate models

+ The best-performing models are located at the bottom for easy review

+ Code is written for clarity and reproducibility

## 📚 References

[XGBoost Official Documentation](https://xgboost.readthedocs.io/en/stable/parameter.html)

[Scikit-learn documentation](https://scikit-learn.org/stable/getting_started.html)

## 👤 Author

**Robert Uwitonze** <br>
Data Science & Machine Learning

If you have suggestions or need clarification, feel free to reach out.