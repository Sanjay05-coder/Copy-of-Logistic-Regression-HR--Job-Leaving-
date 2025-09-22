Logistic Regression – HR Employee Leaving Prediction
📌 Project Overview

This project applies Logistic Regression to predict whether an employee will leave a company based on HR data. The analysis focuses on exploring the relationships between various features (such as satisfaction level, evaluation, working hours, and project count) and the likelihood of leaving.

The main insight:

Most features show weak correlations with the target variable.

The satisfaction level is the only feature with a relatively stronger (negative) correlation. This means:

Lower satisfaction → Higher probability of leaving.

Because correlations are generally weak (no feature has |correlation| ≥ 0.8), the model struggles to perform strongly, indicating a poor predictive power of logistic regression for this dataset.

🗂 Dataset

The dataset consists of HR employee information (features such as satisfaction level, evaluation score, project count, average monthly hours, etc.).

Target variable: Left (1 = employee left, 0 = stayed).

(Add dataset source link here if it’s from Kaggle or UCI)

🔍 Analysis Performed

Exploratory Data Analysis (EDA):

Heatmap used to examine correlations between features and the target.

Found that only satisfaction level has noticeable (negative) correlation with leaving.

Model Training (Logistic Regression):

Split dataset into training and testing sets.

Trained logistic regression classifier on HR features.

Model Evaluation:

Confusion matrix used to evaluate performance.

Accuracy, precision, recall, and F1-score calculated.
