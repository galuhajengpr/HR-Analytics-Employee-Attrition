# HR-Analytics-Employee-Attrition

## Project Domain
The project domain is Human Resources (HR) Employee Attrition analysis, specifically focused on understanding and predicting employee churn within an organization. Employee attrition refers to the phenomenon of employees leaving the company for various reasons.

## Business Understanding 
In the HR domain, understanding and addressing employee attrition is crucial for organizations. High attrition rates can lead to increased recruitment costs, loss of institutional knowledge, and a negative impact on company culture. Therefore, it's essential for businesses to analyze employee data and identify patterns that may contribute to attrition.

## Problem Statement
The problem we aim to address is to analyze the employee data and identify factors or patterns that are associated with employee attrition. We want to understand why employees are leaving the company and build a model that can predict which employees are at a higher risk of attrition. This predictive model can help HR departments take proactive measures to retain valuable talent.

## Goals
- Data Exploration and Analysis: Explore and analyze the provided HR dataset to identify trends, patterns, and potential factors contributing to employee attrition.
- Feature Selection: Determine which features (attributes) are most relevant in predicting employee attrition.

## Solution Statement
The solution involves conducting Exploratory Data Analysis (EDA) on the HR dataset to provide insights and recommendations to help the organization reduce employee attrition.

# Data Understanding
HR EMPLOYEE ATTRITION - EDA
Data taken from : https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

In this case study, a HR dataset was sourced from IBM HR Analytics Employee Attrition & Performance which contains employee data for 1,470 employees with various information about the employees. In this section we will try to find the pattern of the employee who're churned.

As stated on the IBM website "This is a fictional data set created by IBM data scientists". Its main purpose was to demonstrate the IBM Watson Analytics tool for employee attrition.

FEATURE DESCRIPTION
- Age - Age of employee
- Attrition - Attrition of employee (Yes, No)
- BusinessTravel - Frequency of business travel (Non-Travel, Travel_Rarely, Travel_Frequently)
- DailyRate - Amount of money a company has to pay employee to work for them for a day
- Department - Part of an company that deals with a particular area of work(Research & Development, Sales, Human Resources)
- DistanceFromHome - Distance between company and home
- Education - Level of education (1: Below College, 2: College, 3: Bachelor, 4: Master, 5: Doctor)
- EducationField - Field of Education (Life Sciences, Medical, Human Resources, Technical Degree, Marketing, Other)
- EmployeeCount - Count of employee (always 1)
- EmployeeNumber - Number of employee
- EnvironmentSatisfaction - Satisfaction of environment (1: Low, 2: Medium, 3: High, 4: Very High)
- HourlyRate - Amount of money a company has to pay employee to work for them for an hour
- JobInvolvement - Level of job involvement (1: Low, 2: Medium, 3: High, 4: Very High)
- JobLevel - Level of job (1~5)
- JobRole - Role of job (Sales Executive, Research Scientist, Laboratory Technician, Manager, Healthcare Representative, Sales Representative, Manufacturing Director, Human Resources, Manager)
- JobSatisfaction - Satisfaction of job (1: Low, 2: Medium, 3: High, 4: Very High)
- MaritalStatus - Fact of employee being married or not (Married, Divorced, Single)
- MonthlyIncome - Income of Month
- MonthlyRate - Amount of money a company has to pay employee to work for them for a month
- NumCompaniesWorked - Length of service
- Over18 - Over 18 years old (Y, N)
- OverTime - After the usual time needed or expected in a job (Yes, No)
- PercentSalaryHike - Percent of salary of hike
- PerformanceRating - Level of performance assessment (1: Low, 2: Good, 3: Excellent, 4: Outstanding)
- RelationshipSatisfaction - Level of relationship satisfaction (1: Low, 2: Medium, 3: High, 4: Very High)
- StandardHours - Standard work hours (always 80)
- StockOptionLevel - Stock option level (0~3)
- TotalWorkingYears - Years of total working
- TrainingTimesLastYear - Training times of last year
- WorkLifeBalance - Level of work life balance (1: Bad, 2: Good, 3: Better, 4: Best)
- YearsAtCompany - Years at company
- YearsInCurrentRole - Years in current role
- YearsSinceLastPromotion - Years since last promotion
- YearsWithCurrManager - Years with current manager
