# Titanic Survival Prediction 🚢
This project predicts the likelihood of passenger survival aboard the Titanic using machine learning techniques. Leveraging the well-known Titanic dataset, it demonstrates the application of data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling.

## Introduction
The sinking of the Titanic is one of the most infamous disasters in history. By analyzing a dataset of passengers' details, this project predicts who was more likely to survive based on factors such as age, gender, passenger class, and more.

This project is ideal for learning the end-to-end process of building a machine learning model.


## Dataset
The dataset is sourced from Kaggle's Titanic Challenge.
It contains the following features:

PassengerId: Unique ID for each passenger , 
Survived: Target variable (0 = Not Survived, 1 = Survived) ,
Pclass: Ticket class (1st, 2nd, or 3rd) ,
Name: Passenger's name ,
Sex: Gender ,
Age: Age of passenger ,
SibSp: Number of siblings/spouses aboard ,
Parch: Number of parents/children aboard ,
Ticket: Ticket number ,
Fare: Fare paid for the ticket ,
Cabin: Cabin number (if available) ,
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) 


## Project Workflow
1. Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.
2. Exploratory Data Analysis (EDA): Analyze and visualize key trends in the dataset.
3. Feature Engineering: Derive meaningful features to improve prediction accuracy.
4. Model Building: Train and evaluate machine learning models (e.g., Logistic Regression, Random Forest, etc.).
5. Evaluation: Use metrics like accuracy, precision, recall, and F1-score to assess model performance.

## Results
The best-performing model achieves an accuracy of XX% on the test set, with the following key insights:

Gender: Women had higher survival rates.

Passenger Class: Passengers in 1st class were more likely to survive than those in 2nd or 3rd class.

Family Size: Moderate family size positively impacted survival likelihood.


