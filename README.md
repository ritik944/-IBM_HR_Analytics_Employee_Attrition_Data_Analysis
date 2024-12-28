# IBM HR Analytics: Employee Attrition & Performance

This project analyzes IBM's HR data to understand key factors contributing to employee attrition and performance. By leveraging data science tools, we explore patterns in employee characteristics and predict attrition risk.

## Table of Contents
- [Overview](#overview)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [License](#license)

## Overview
This project investigates the factors that affect employee attrition at IBM. It uses data analysis and visualization techniques to uncover trends and potential insights that can help the company retain valuable employees.

## Technologies
- **Python**: For data manipulation and analysis.
- **Jupyter Notebook**: For interactive exploration and visualization.
- **Pandas, NumPy**: Libraries for data manipulation and statistical analysis.
- **Matplotlib, Seaborn**: Libraries for data visualization.
- **Scikit-learn**: For machine learning and predictive modeling (if applicable).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ritik944/IBM_HR_Data_Analysis.git
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt

## Usage
- Open the Jupyter notebook (IBM.ipynb) to explore the analysis.
- Run the cells step-by-step to understand the data exploration and visualization process.
- Modify the notebook to analyze different attributes and their impact on attrition.

## Dataset
The dataset used is IBM's HR employee attrition data (WA_Fn-UseC_-HR-Employee-Attrition.csv). It includes various features such as:
- Age
- Job Role
- Job Satisfaction
- Work-life balance
- Overtime status
- Years at company

## Results
- The workers with low JobLevel, MonthlyIncome, YearAtCompany, and TotalWorkingYears are more likely to quit there jobs.
- BusinessTravel : The workers who travel alot are more likely to quit then other employees.
- Department : The worker in Research & Development are more likely to stay then the workers on other departement.
- EducationField : The workers with Human Resources and Technical Degree are more likely to quit then employees from other fields of educations.
- Gender : The Male are more likely to quit.
- JobRole : The workers in Laboratory Technician, Sales Representative, and Human Resources are more likely to quit the workers in other positions.
- MaritalStatus : The workers who have Single marital status are more likely to quit the Married, and Divorced.
- OverTime : The workers who work more hours are likely to quit then others..
- Potential predictive models for identifying employees at risk of attrition (if applicable).
- RANDOM FOREST                  roc_auc_score: 0.543
- XGBOOST                        roc_auc_score: 0.619
- LOGISTIC REGRESSION            roc_auc_score: 0.546
- SUPPORT VECTOR MACHINE         roc_auc_score: 0.500
- ADABOOST                       roc_auc_score: 0.599
