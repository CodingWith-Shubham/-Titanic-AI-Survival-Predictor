# Titanic - Machine Learning from Disaster 

This project is a solution for the **Kaggle Titanic: Machine Learning from Disaster** competition. The goal is to predict which passengers survived the Titanic shipwreck using classification models.

## 🧾 About the Competition

The Titanic dataset is one of the most iconic beginner datasets. It challenges participants to build a model that predicts survival using passenger data such as age, sex, class, etc.

##  Project Highlights

- Cleaned and preprocessed raw data
- Performed feature engineering
- Trained and evaluated machine learning models
- Used accuracy and cross-validation to assess performance
- Submitted predictions to Kaggle

## 🗂️ Dataset

Available on [Kaggle Titanic Page](https://www.kaggle.com/competitions/titanic)

- `train.csv` – Training dataset with features and labels  
- `test.csv` – Testing dataset (no labels provided)  
- `gender_submission.csv` – Sample submission file

##  Preprocessing Steps

- Filled missing values (Age, Embarked)
- Converted categorical data (Sex, Embarked) using encoding
- Created new features (e.g., FamilySize, IsAlone)
- Scaled numerical features if needed

##  Models Used

- Random Forest Classifier
- K-Nearest Neighbors (optional)
- GridSearchCV for hyperparameter tuning (optional)

##  Evaluation

- Used accuracy score and confusion matrix
- Performed cross-validation for model robustness
- Achieved competitive accuracy on the Kaggle public leaderboard

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/titanic-ai-predictor.git
   cd titanic-ai-predictor
