# Machine-Learning-Models-on-iPhone-Purchases-Dataset

In this project, I used Scikit-learn to build an SVM classifier that predicts whether a user will purchase an iPhone based on their age and salary. After running cross-validation and grid search, I found that a C value of 0.60 and a tolerance value of 0.90 gave the highest classification accuracy for this model.


## Features
- SVM classifier to predict IPhone purchases from age and salary
- N fold cross validation to evaluate model performance
- Grid search over C and tolerance hyperparameters to select the best configuration

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

## How to Run
1. Clone the repository
2. Open the juypter notebook (`.ipynb` file) in Jupyter or VS Code.
3. Run all cells to reproduce data loading, model training, and evaluation.

## What I implemented
- Built an SVM classifier with Scikit-learn to predict iPhone purchases
- Implemented N fold cross-validation and grid search over C and tolerance values to select the best model configuration
-  Performed an 80/20 train–test split and scaled features using `StandardScaler` with `fit_transform` on the training set
