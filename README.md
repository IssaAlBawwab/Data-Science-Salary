# Data Science Salary
 Analysing and Predicting Salaries of Data Science Roles
 - Dataset link: https://ai-jobs.net/salaries/download/
# Predictive Modeling of Data Science Salaries

## Introduction

This project aims to analyze a dataset containing salary information for data science roles across various factors like experience level, employment type, job title, and more. The goal is to build a predictive model to estimate salaries within this field accurately.

## Data Dictionary

### Fields and Descriptions

- **work_year**
  - **Description:** The year the salary was paid.
  - **Type:** Year (e.g., 2021, 2022)

- **experience_level**
  - **Description:** The experience level in the job during the year.
  - **Possible Values:**
    - `EN` - Entry-level / Junior
    - `MI` - Mid-level / Intermediate
    - `SE` - Senior-level / Expert
    - `EX` - Executive-level / Director

- **employment_type**
  - **Description:** The type of employment for the role.
  - **Possible Values:**
    - `PT` - Part-time
    - `FT` - Full-time
    - `CT` - Contract
    - `FL` - Freelance

- **job_title**
  - **Description:** The role worked in during the year.
  - **Type:** Text (e.g., Software Engineer, Data Scientist)

- **salary**
  - **Description:** The total gross salary amount paid.
  - **Type:** Numeric

- **salary_currency**
  - **Description:** The currency of the salary paid as an ISO 4217 currency code.
  - **Type:** ISO 4217 currency code (e.g., USD, EUR)

- **salary_in_usd**
  - **Description:** The salary in USD, adjusted by the average exchange rate for the respective year.
  - **Type:** Numeric

- **employee_residence**
  - **Description:** Employee's primary country of residence during the work year.
  - **Type:** ISO 3166 country code (e.g., US, GB)

- **remote_ratio**
  - **Description:** The overall amount of work done remotely.
  - **Possible Values:**
    - `0` - No remote work (less than 20%)
    - `50` - Partially remote/hybrid
    - `100` - Fully remote (more than 80%)

- **company_location**
  - **Description:** The country of the employer's main office or contracting branch.
  - **Type:** ISO 3166 country code (e.g., US, GB)

- **company_size**
  - **Description:** The average number of people that worked for the company during the year.
  - **Possible Values:**
    - `S` - less than 50 employees (small)
    - `M` - 50 to 250 employees (medium)
    - `L` - more than 250 employees (large)
## Data Preprocessing

### Cleaning
- Handle missing or null values.
- Convert categorical data into a suitable format for modeling (e.g., one-hot encoding).

## Exploratory Data Analysis (EDA)

- Statistical summary of the data.
- Distribution of salaries.

## Model Building

- Selection of suitable models for salary prediction (e.g., xgboost, random forest).
- Splitting the dataset into training and testing sets.
- Model training and parameter tuning.

## Model Evaluation

- Evaluation metrics (e.g., RMSE).
- Comparison of model performances.

## Conclusion

- Summary of findings.
- Insights into factors influencing data science salaries.

