
# Credit Card Fraud Detection

## Project Overview
Credit Card Fraud Detection is a Machine Learning project that identifies fraudulent credit card transactions based on transaction data. The goal is to build a classification model that can distinguish between genuine and fraudulent transactions.

## Objective
* Preprocess transaction data.
* Handle missing values.
* Normalize numerical features.
* Train a Machine Learning model.
* Detect fraudulent transactions.
* Evaluate model performance using classification metrics.

## Dataset
The dataset contains credit card transaction records with the following features:
* **Time** – Time elapsed between transactions.
* **V1 - V28** – Anonymized features obtained using PCA transformation.
* **Amount** – Transaction amount.
* **Class** – Target variable:
  * 0 → Genuine Transaction
  * 1 → Fraudulent Transaction

**Note:** The dataset is not included in this repository due to its large size.
Download the dataset from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Place the downloaded `creditcard.csv` file in the project directory before running the notebook.

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Machine Learning Algorithm
* Logistic Regression

## Project Workflow
### 1. Data Collection
Load the credit card transaction dataset.
### 2. Data Preprocessing
* Handle missing values
* Separate features and target variable
* Scale numerical columns
### 3. Train-Test Split
Split the dataset into:
* 80% Training Data
* 20% Testing Data
### 4. Model Training
Train a Logistic Regression model using the training dataset.
### 5. Prediction
Predict whether a transaction is fraudulent or genuine.
### 6. Model Evaluation
Evaluate the model using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
## Sample Results
Accuracy: 99.94%
Precision: 84.62%
Recall: 78.57%
F1-Score: 81.48%

## Project Structure
Task3_CreditCardFraudDetection/
├── task3_CreditCardFraudDetection.ipynb
├── readme.md
├── .gitignore

## How to Run
1. Install required libraries:
pip install pandas numpy scikit-learn
2. Download the dataset from Kaggle.
3. Place `creditcard.csv` in the project folder.
4. Open and run:
task3_CreditCardFraudDetection.ipynb

## Conclusion
This project demonstrates how Machine Learning can be used to identify fraudulent credit card transactions. The trained model helps detect suspicious activities and can assist financial institutions in reducing financial fraud.

## Author
Gopu Sankeerthana 

Data Science Intern | CodSoft
