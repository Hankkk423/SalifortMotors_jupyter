# Solifort Motors: Employee Attrition Prediction

## Introduction

Employee turnover, especially in critical positions, can significantly impact a company's performance and morale. High turnover rates often signal underlying issues such as dissatisfaction, poor management, or lack of growth opportunities. In this project, we aim to analyze employee data to predict which employees are likely to leave the company and identify key factors contributing to their decision.

Understanding why employees leave and being able to predict turnover can help companies take proactive measures to retain valuable talent, improve employee satisfaction, and ultimately enhance organizational stability and productivity.

By leveraging machine learning techniques on historical employee data, we can develop predictive models that identify patterns and trends associated with turnover. These models can then be used to flag employees at risk of leaving, allowing HR departments and management to intervene with targeted retention strategies.

In addition to predicting turnover, we also aim to uncover insights into the factors influencing employee decisions to leave. By analyzing features such as job satisfaction, performance evaluations, workload, tenure, and promotion opportunities, we can gain valuable insights into the drivers of employee turnover.

Ultimately, the goal of this project is to provide actionable insights and recommendations to help companies reduce turnover, improve employee satisfaction, and foster a more positive and productive work environment.

## Dataset

The dataset used for this analysis is provided in the file `HR_dataset.csv`. It includes the following columns:

- `satisfaction_level`: Employee-reported job satisfaction level, ranging from 0 to 1.
- `last_evaluation`: Score of the employee's last performance review, ranging from 0 to 1.
- `number_project`: Number of projects the employee contributes to.
- `average_monthly_hours`: Average number of hours the employee worked per month.
- `time_spend_company`: Duration of the employee's tenure with the company in years.
- `Work_accident`: Binary variable indicating whether the employee experienced an accident while at work (1 for yes, 0 for no).
- `left`: Binary variable indicating whether the employee left the company (1 for yes, 0 for no).
- `promotion_last_5years`: Binary variable indicating whether the employee was promoted in the last 5 years (1 for yes, 0 for no).
- `Department`: The employee's department.
- `salary`: The employee's salary in U.S. dollars.

## Analysis

### Part 1: Exploratory Data Analysis (EDA)

Explored the dataset, checked for missing values, and visualized the distribution of key features.

### Part 2: Data Preprocessing and Encoding

Cleaned the data, handled categorical variables, and encoded them for model training.

### Part 3: Modeling Approach

Implemented a Logistic Regression model and evaluated its performance using precision, recall, f1-score, and accuracy metrics. Checked class balance in the data and created a classification report.

Implemented Decision Tree and Random Forest models using a tree-based approach. Conducted hyperparameter tuning using GridSearchCV and evaluated model performance.

### Part 4: Results and Evaluation

Continued with feature engineering, making the `overworked` column binary and dropping the `average_monthly_hours` column. Built and evaluated Decision Tree - Round 2 and Random Forest - Round 2 models.

Summarized model results, interpreted feature importance, and provided recommendations based on the analysis.

## Conclusion, Recommendations, Next Steps

Concluded with key insights from the models and recommendations to retain employees, such as capping project numbers, promoting long-term employees, and addressing workload issues.

---

### Reflect on the Analysis

- Key insights emerged from the models, identifying factors contributing to employee attrition.
- Business recommendations were proposed based on model results.
- Potential recommendations to the company were provided.
- The model could be improved by collecting additional data, refining features, and continuous monitoring.
- Future questions could address team-specific attrition patterns and gather qualitative data.
- Resources used include scikit-learn, pandas, and matplotlib/seaborn for visualization.
- Ethical considerations involve ensuring fairness and transparency in decision-making based on model predictions.

---

**Note:** The snippets provided above are summaries. For detailed code, please refer to the Jupyter Notebook file.
