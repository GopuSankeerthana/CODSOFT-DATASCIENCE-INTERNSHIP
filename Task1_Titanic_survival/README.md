# Titanic Survival Prediction using Decision Tree Classifier

## Project Overview
This project applies Machine Learning techniques to predict whether a passenger survived the Titanic disaster. Using passenger information such as class, gender, age, and fare, a Decision Tree Classifier is trained to identify survival patterns and make predictions for new passengers.

## Objective
The objective of this project is to build a classification model capable of predicting passenger survival based on historical Titanic passenger data.

## Dataset
The Titanic dataset contains information about passengers aboard the Titanic, including:
- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Embarked Location
- Survival Status

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## Data Preprocessing
The following preprocessing steps were performed:
- Missing values in the Age column were replaced with the median value.
- Missing values in the Fare column were replaced with the median value.
- Missing values in the Embarked column were replaced with the most frequent value.
- Categorical features were converted into numerical values for model training.

### Encoding
| Feature      | Encoding |
|--------------|----------|
| Male         | 0        |
| Female       | 1        |
| Embarked (S) | 0        |
| Embarked (C) | 1        |
| Embarked (Q) | 2        |

## Features Used
The model was trained using the following features:
- Pclass
- Sex
- Age
- Fare
## Target Variable
- Survived

## Machine Learning Model
A Decision Tree Classifier was used with the following configuration:
- Maximum Depth: 5
- Random State: 0

## Project Workflow
1. Load the Titanic dataset
2. Explore and understand the data
3. Handle missing values
4. Encode categorical variables
5. Select relevant features
6. Split data into training and testing sets
7. Train the Decision Tree model
8. Evaluate model performance
9. Predict survival for new passengers

## Sample Prediction

## Passenger Information
- Passenger Class: First Class
- Gender: Female
- Age: 25 Years
- Fare: $80
The trained model predicts whether the passenger is likely to survive and provides the probability of survival.

## Project Structure
text Task1_Titanic_Survival/ |- Titanic_Prediction.ipynb |- Titanic-Dataset.csv └── README.md 

## Learning Outcomes
- Data Cleaning and Preprocessing
- Handling Missing Values
- Feature Selection
- Classification using Decision Trees
- Model Evaluation and Prediction
- Working with Real-World Datasets

## Author
Gopu Sankeerthana

Data Science Intern | CodSoft
