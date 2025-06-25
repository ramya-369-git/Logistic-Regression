# Logistic Regression on Titanic Dataset

## 📋 Overview

This project uses **Logistic Regression** to predict passenger survival on the Titanic based on features like age, sex, passenger class, and more. The dataset is a classic benchmark for binary classification tasks in machine learning.

## 🎯 Objectives

- Apply Logistic Regression for binary classification.
- Predict survival (`Survived`: 0 = No, 1 = Yes) based on passenger features.
- Preprocess and encode categorical data.
- Evaluate model performance using standard classification metrics.

## 📊 Dataset

The **Titanic dataset** is a built-in dataset available via `sklearn.datasets`. It includes features such as:

- `Pclass` – Passenger class (1st, 2nd, 3rd)
- `Sex` – Gender
- `Age` – Age of the passenger
- `SibSp`, `Parch` – Number of relatives aboard
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation
- `Survived` – Target variable (0 or 1)

## 🛠️ Tools & Technologies

- Language: Python  
- Libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`  
- Environment: Jupyter Notebook

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook or JupyterLab.
3. Run the cells to load the data, preprocess, train the model, and evaluate the results.

## 📌 Future Improvements

- Tune hyperparameters using Grid Search.
- Handle missing values and outliers more robustly.
- Compare Logistic Regression with other classifiers like Decision Trees or SVM.
- Visualize ROC Curve and compute AUC score.

## 📄 License

This project is open-source and intended for educational and academic use.
