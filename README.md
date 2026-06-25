# codveda-ml-internship
Machine Learning internship tasks for Codveda Technology
# Codveda Machine Learning Internship

Hey! This repo has all the work I did for my Machine Learning internship at Codveda Technology in June 2026.

I went with the option of doing 2 tasks per level (6 total), and tried to keep each notebook focused and runnable end-to-end in Google Colab. Everything here was built with Python, mostly using pandas, scikit-learn, and TensorFlow/Keras for the deep learning part.

## What's inside

Level 1 (Basic)
- Task 1 — Data preprocessing pipeline on the Titanic dataset (handling missing values, encoding categoricals, scaling, train/test split) → level1_task1_preprocessing/
- Task 2 — Linear regression on California housing prices → level1_task2_linear_regression/

Level 2 (Intermediate)
- Task 1 — Logistic regression for binary classification on the Breast Cancer dataset → level2_task1_logistic_regression/
- Task 2 — Decision tree classifier on the Iris dataset (with GridSearchCV for pruning) → level2_task2_decision_tree/

Level 3 (Advanced)
- Task 1 — Random Forest classifier on the Wine dataset, with hyperparameter tuning and feature importance analysis → level3_task1_random_forest/
- Task 3 — Feed-forward neural network on MNIST using TensorFlow/Keras → level3_task3_neural_network/

## How it went

| Task | Model | Dataset | Result |
|---|---|---|---|
| L1-T1 | Preprocessing pipeline | Titanic | Train (712, 20) / Test (179, 20) |
| L1-T2 | Linear Regression | California Housing | R² = 0.576 |
| L2-T1 | Logistic Regression | Breast Cancer | Accuracy 0.982, AUC 0.995 |
| L2-T2 | Decision Tree | Iris | Accuracy 0.933, F1 0.933 |
| L3-T1 | Random Forest | Wine | Accuracy 1.00, CV F1 0.986 |
| L3-T3 | Neural Network (Keras) | MNIST | Test Accuracy 0.978 |

Random Forest hitting 100% on the test set was a nice surprise (Wine is a pretty separable dataset though). The neural net on MNIST plateaued around 98% which is what I expected from a simple feed-forward architecture without convolutions.

## Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, TensorFlow/Keras.

## Running the notebooks

Each task has its own folder with a Jupyter notebook. The fastest way to run them is to open the .ipynb file in Google Colab (no setup needed, all libraries are pre-installed) and hit Runtime → Run all.

## About me

I'm Memucan Kiprono, based in Nairobi, Kenya. Big thanks to the Codveda team for putting this internship together — it pushed me to actually ship things end-to-end instead of just reading tutorials.

#CodvedaJourney #CodvedaExperience #FutureWithCodveda
