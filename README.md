Titanic Survival Prediction 🚢

This repository contains a machine learning project based on the Titanic: Machine Learning from Disaster dataset. The main objective of this project is to predict passenger survival using data preprocessing, feature engineering, and classification algorithms.

📂 Project Structure

Titanic-Survival-Prediction.ipynb → Jupyter Notebook with the complete workflow (data preprocessing, feature engineering, model training & evaluation).

README.md → Documentation of the project.

Titanic-dataset → Directory to store dataset files.

📊 Dataset

The dataset is the well-known Titanic dataset available on Kaggle
.
It contains information about passengers such as:

PassengerId: Unique ID

Pclass: Ticket class (1st, 2nd, 3rd)

Name: Passenger’s name

Sex: Gender

Age: Passenger’s age

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Ticket price

Cabin: Cabin number

Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

Survived: Target variable (0 = No, 1 = Yes)

🛠️ Data Preprocessing

Missing Values Handling

Filled missing values in Age, Embarked, and Fare.

Dropped irrelevant features (PassengerId, Name).

Categorical Encoding

Converted categorical variables (Sex, Embarked, etc.) into numerical format using Label Encoding.

Feature Engineering

🤖 Machine Learning Models

Two classification algorithms were implemented:

Logistic Regression

Baseline model to predict survival probabilities.

XGBoost Classifer

Ensemble learning method providing higher accuracy and better feature importance insights.

📈 Model Evaluation

Accuracy, Precision, Recall, and F1-score were calculated for each model.

Confusion matrices and classification reports were used to compare performances.

Model	Accuracy
Logistic Regression	~77%
XGBoost Classifier	~82%

🚀 How to Run

Clone this repository:

git clone https://github.com/bhagyasri1609/titanic-survival-prediction.git
cd titanic-survival-prediction


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Titanic-Survival-Prediction.ipynb

📌 Conclusion

The project demonstrates handling of categorical variables, missing values, and feature engineering.

Two classification algorithms were applied, and XGBoost Classifier achieved better performance compared to Logistic Regression.
