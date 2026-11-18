# HR Employee Churn Predictor

This project uses machine learning to predict employee attrition from HR data. The goal is to understand which factors influence employees leaving an organization and to build a model that can flag employees at risk of churn.

## Project Overview

The analysis is carried out in the notebook [Employee_Churn_Prediction_Analysis.ipynb](Employee_Churn_Prediction_Analysis.ipynb) using the dataset file [Human_Resources.csv](Human_Resources.csv).

The project combines:
- data cleaning and preprocessing,
- exploratory data analysis,
- feature engineering,
- model training and evaluation,
- interpretation of results for HR and workforce planning.

## Dataset

The dataset used in this project is the IBM HR Analytics Attrition Dataset.

Download link:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Objectives

This project aims to:
- explore the patterns behind employee attrition,
- identify the most important factors contributing to churn,
- compare different machine learning models,
- build a prediction workflow that could support HR decision-making.

## Files in This Project

- [Employee_Churn_Prediction_Analysis.ipynb](Employee_Churn_Prediction_Analysis.ipynb) – main notebook containing the full analysis and modeling workflow.
- [Human_Resources.csv](Human_Resources.csv) – dataset used for training and analysis.
- [README.md](README.md) – project documentation.

## What Improvements Were Made

Compared to a basic exploratory analysis, this project includes several improvements:

- cleaned the dataset by removing irrelevant or constant features such as EmployeeCount, StandardHours, Over18, and EmployeeNumber,
- prepared the data for modeling by handling categorical features,
- used one-hot encoding for non-numeric variables,
- split the dataset into training and testing sets,
- trained and evaluated multiple classification models,
- assessed performance using metrics such as accuracy, confusion matrix, and classification report,
- explored class imbalance and the importance of handling churn cases carefully.

## Comparisons Made

The notebook compares different machine learning approaches for predicting attrition, including:

- Logistic Regression
- Random Forest Classifier

The comparison focuses on:
- prediction accuracy,
- confusion matrix results,
- ability to correctly identify employees who may leave,
- overall model reliability on unseen test data.

The project also explores the challenge of imbalanced data, since attrition is usually less frequent than retention.

## Key Findings and Insights

From the analysis, some important patterns emerged:

- employees who left the company tended to be younger on average,
- employees who stayed generally reported higher job satisfaction and environment satisfaction,
- distance from home appeared to be a relevant factor,
- employees who stayed were more likely to have stronger stock option levels,
- attrition is a relatively rare event, so prediction should be evaluated carefully rather than relying only on overall accuracy.

## What I Learned From This Project

This project helped to build a stronger understanding of:

- how HR and employee behavior data can be transformed into predictive insights,
- the importance of data cleaning and feature selection,
- how classification models can support workforce decision-making,
- why business context matters when interpreting model results,
- the importance of considering imbalance and false positives/false negatives in churn prediction.

## Real-World Fit

This type of project is highly relevant in the real world because employee turnover can be expensive for organizations. A churn prediction model can help businesses:

- identify employees who may leave soon,
- support retention strategies before employees resign,
- improve workforce planning and HR decision-making,
- reduce hiring and training costs,
- focus employee engagement efforts on high-risk groups.

In practice, this model could be used by HR teams, people analytics departments, and business leaders to make data-driven retention decisions.

## How to Run the Notebook

Make sure you have Python installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Then start Jupyter Notebook:

```bash
jupyter notebook
```

Open [Employee_Churn_Prediction_Analysis.ipynb](Employee_Churn_Prediction_Analysis.ipynb) and run the cells.

## Future Improvements

Possible next steps for this project include:

- tuning model hyperparameters for better performance,
- comparing more models such as Gradient Boosting or XGBoost,
- creating visualizations for feature importance,
- handling class imbalance more explicitly,
- building a simple dashboard or web app for HR use,
- deploying the model in a real organizational workflow.

##Phathu Loves You
