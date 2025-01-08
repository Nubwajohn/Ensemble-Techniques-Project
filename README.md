# Ensemble-Techniques-Project
Ensemble Techniques Project: EasyVisa.

## About

Business communities in the U.S. face challenges in identifying and attracting qualified talent, both locally and abroad, which is critical for staying competitive. The Immigration and Nationality Act (INA) allows foreign workers to fill workforce shortages, with the Office of Foreign Labor Certification ensuring compliance and protecting U.S. workers' wages and conditions through job certification applications.

*Disclaimer: All datasets and reports do not represent any company, institution, or country, but just a dummy dataset for learning purposes.*

## Project Overview

Analyze the data and use a classification model to streamline visa approvals by recommending whether an applicant should be certified or denied, based on the key factors that influence the case status..

OFLC processes job certification applications for employers seeking to bring foreign workers into the United States and grants certifications in those cases where employers can demonstrate that there are not sufficient US workers available to perform the work at wages that meet or exceed the wage paid for the occupation in the area of intended employment.

## Data Sources

The data contains the different attributes of the employee and the employer in the “EasyVisa.csv.”.  The detailed data dictionary is given below..

**Data Dictionary**

- case_id: ID of each visa application
- continent: Information of continent the employee
- education_of_employee: Information of education of the employee
- has_job_experience: Does the employee has any job experience? Y= Yes; N = No
- requires_job_training: Does the employee require any job training? Y = Yes; N = No
- no_of_employees: Number of employees in the employer's company
- yr_of_estab: Year in which the employer's company was established
- region_of_employment: Information of foreign worker's intended region of employment in the US.
- prevailing_wage:  Average wage paid to similarly employed workers in a specific occupation in the area of intended employment. The purpose of the prevailing wage is to ensure that the foreign worker is not underpaid compared to other workers offering the same or similar service in the same area of employment.
- unit_of_wage: Unit of prevailing wage. Values include Hourly, Weekly, Monthly, and Yearly.
- full_time_position: Is the position of work full-time? Y = Full Time Position; N = Part Time Position
- case_status:  Flag indicating if the Visa was certified or denied

## Tools

- Programming Language: Python.
- Data Manipulation & Analysis Libraries: Pandas, NumPy.
- Data Visualization Libraries: Matplotlib, Seaborn.
- Machine Learning Library: Scikit-Learn, sklearn.
- Metric scores: sklearn.metrics, confusion_matrix, accuracy_score, precision_score, recall_score, f1_score.
- Ensemble classifiers: BaggingClassifier, RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, StackingClassifier, XGBClassifier, DecisionTreeClassifier.
- Tune models: GridSearchCV.
- Filtering Warnings: warnings, ConvergenceWarning.
- Data Preprocessing & Exploratory Data Analysis (EDA) Tools:Excel, Google Colab.
