# Loan Approval Prediction Project

## Abstract:
This project aims to predict whether a loan application will be approved or not, addressing a typical classification problem. It serves as a practice exercise for honing data analytics skills and gaining a deeper understanding of machine learning algorithms and concepts.

## Data Collection:
The project utilizes two main data source files: `train_file_loan.csv` and `test_file_loan.csv`, containing semi-clean data available on Kaggle. Additionally, several PNG files are included for data visualization purposes, along with various CSV files for storing the results.

## Libraries Used:
- Pandas
- NumPy
- Seaborn
- Matplotlib (For Exploratory Data Analysis and Visualization)
- Scikit-learn (Sklearn)
- Scikit-learn Metrics
- StratifiedKFold (For evaluating the models)

## Data Types for Visualization:
1. **Categorical:**
   - Gender
   - Married (Yes/No)
   - Self-employed (Yes/No)
   - Credit history (0.0, 1.0)

2. **Ordinal:**
   - Dependent (1, 2, 3, 4)
   - Education (Graduate, Not Graduate)
   - Property (Rural, Urban, Semiurban)

3. **Numerical:**
   - Applicant income
   - Loan amount

## Model Selection:
The project employs the following machine learning models:
- Logistic Regression
- Decision Tree
- Random Forest

Evaluation of the models is done using StratifiedKFold.

## Results:
Random Forest achieves the highest accuracy of 80% among the models evaluated.

## Reference:
This project is inspired by the Loan Prediction project available on Analytics Vidhya.
