# PIMA-Diabetes-Prediction

This repository contains an end-to-end Machine Learning pipeline for predicting diabetes using the PIMA Indian Diabetes dataset. The dataset includes health-related attributes such as:

Pregnancies

Glucose level

Blood pressure

Skin thickness

Insulin levels

BMI

Diabetes pedigree function

Age

🧰 Workflow
🧼 Data Exploration & Preprocessing:
Descriptive statistics for all variables

Visualization using histograms, boxplots, and density plots

Checked and handled missing/null values

Standardized features where necessary

🔀 Train-Test Split & Pipelines:
Used train_test_split from scikit-learn

Applied Pipeline for streamlined preprocessing and modeling

🤖 Models Implemented:
Logistic Regression

Linear Discriminant Analysis (LDA)

K-Nearest Neighbors

Gaussian Naive Bayes

Support Vector Classifier (SVC)

🔁 Model Evaluation:
Accuracy and cross-validation using ShuffleSplit

Ensemble learning techniques: Random Forest, Bagging, and AdaBoost

Compared model performance metrics (accuracy, precision, recall)

📈 Results
Visual comparison of model performance

Noted insights on which models performed best for this dataset

🛠 Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn
