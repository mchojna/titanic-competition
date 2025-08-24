# Titanic - Machine Learning from Disaster

This repository contains code and notebooks for the Kaggle competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic). The goal of the competition is to predict whether a passenger on the Titanic survived or not based on various features such as age, gender, class, etc.

## Repository Structure

The repository is organized as follows:

- **`titanic_exploring.ipynb`**: A Jupyter Notebook dedicated to exploring the dataset. It includes:
  - Data overview and feature descriptions.
  - Exploratory Data Analysis (EDA) to understand the relationships between features and survival status.

- **`titanic_modeling.ipynb`**: A Jupyter Notebook focused on building and evaluating machine learning models. It includes:
  - Data preprocessing and feature engineering.
  - Implementation of various classification models such as Logistic Regression, Naive Bayes, and Linear Discriminant Analysis.
  - Hyperparameter tuning and cross-validation.
  - Model evaluation using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

## Dataset

The dataset used in this project is publicly available on Kaggle and contains the following files:
- `train.csv`: Training dataset with features and survival labels.
- `test.csv`: Test dataset for making predictions.

### Key Features in the Dataset:
- `PassengerId`: Unique ID for each passenger.
- `Survived`: Target variable (1 = Survived, 0 = Did not survive).
- `Pclass`: Ticket class (1st, 2nd, 3rd).
- `Name`: Passenger's name.
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Fare`: Ticket fare.
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
