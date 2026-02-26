# data-analytics-internship-tasks
# Task 1: Exploring and Visualizing Iris Dataset

## Objective
To understand dataset structure and visualize relationships between variables.

## Approach
- Loaded dataset using seaborn
- Used pandas for inspection
- Created scatter plot, histogram, and box plot

## Key Insights
- Petal measurements clearly separate species
- Dataset has no missing values
- Distribution appears normal for most features


# Task 2: Credit Risk Prediction

## Objective
To predict whether a loan applicant will be approved based on financial and personal details.

## Dataset Features
- Age
- Income
- Credit_Score
- Loan_Amount
- Loan_Term
- Employment_Status
- Loan_Approved (Target Variable)

## Approach

1. Data inspection (no missing values found)
2. Label encoding for categorical variable (Employment_Status)
3. Exploratory Data Analysis (histograms and box plots)
4. Feature scaling using StandardScaler
5. Logistic Regression model training
6. Model evaluation using Accuracy and Confusion Matrix

## Key Insights

- Credit score and income significantly impact loan approval.
- Feature scaling improved model convergence.
- The model achieved an accuracy of 0.9125%.
- Logistic Regression performs well for this binary classification problem.

## Tools Used
- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn