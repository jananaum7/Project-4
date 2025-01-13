# Credit Score Classification

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting_started)
3. [Project Imports & Requirement](#project_imports_&_requirement)
4. [Project Overview](#project_overview)
5. [Contributers](#contributers)
6. [References](#references)

## Introduction
This project takes a closer look at financial data to better understand the relationship between credit scores, interest rates, and any unusual patterns or outliers that might stand out. Using Jupyter Notebook, we analyze the dataset to uncover meaningful trends and correlations that can offer valuable insights. The goal is to help customers make more informed financial decisions by showing how credit scores can affect interest rates and highlighting any irregularities in the data. By digging into these details, we aim to provide practical insights that can support smarter financial planning and strategies.

## Getting Started
1. Create the Project-4 repository on github.
2. Clone the Repository: Open Git Bash and navigate to the directory where you want to store the project. Use the following command to clone the repository:
   ``` bash
         git clone git@github.com:jananaum7/Project-4.git
   ```
3. Create your individual branches.
    ``` bash
        git checkout main
    ```
    ``` bash
        git branch branch-name
    ```
    ``` bash
        git checkout branch-name
    ```
    ``` bash
        git branch
    ```
    ``` bash
        git push -u origin branch-name
    ```
5. Create resources folder
   ``` bash
       mkdir Resources
   ```
6. Open Jupyter notebook and create a main_analysis.ipynb
7. Start coding!

## Project Imports
1. os & re: for file management and regular expression operations to handle data and paths.
2. Pandas & Numpy: for data manipulation, analysis, and numerical operations.
3. Scikit-learn: provides tools for **splitting datasets** (train_test_split) and **scaling data** (StandardScaler).
4. TensorFlow: Used for building, training, and evaluating machine learning models.
5. SQLAlchemy: For connecting and interacting with databases.
6. Requirement: Python Matplotlib

## Project Overview
1. Data Cleaning:
   - Used ‘infer_objects’ to automatically detect and convert mixed-type columns.
   - Null values removed, unrecognizable characters removed, typos or non-numerical characters removed from number value columns, 
     ‘credit_history_age’ column converted to # of months → ‘credit_history_age_months.
   - ‘credit_history_age’ column dropped.
   - Other columns dropped: ‘SSN’, ‘Occupation’, ‘Age’, ‘Customer_ID’, 'Month', 'Name', 'Changed_Credit_Limit', 'Type_of_Loan', 'Payment_Behaviour'.
   - Cleaned columns: ‘Outstanding_Debt’, ‘Amount_invested_monthly’, ‘Monthly_Balance’ by replacing commas, underscores, and spaces with ‘ ’.

## Contributers
- [Karina Ahumada](https://github.com/karinaahumada01)
- [Tom Bagley](https://github.com/bthomasw)
- [Angelica Guerrero](https://github.com/av9248)
- [Dylon Wilson]()
- [Jana. Naum](https://github.com/jananaum7)


## References

ChatGPT and Xpert Learning Assistant were used for analysis reference and troubleshooting errors for this project assignment.

- OpenAI. (January, 2025). ChatGPT (GPT-4) [Large language model]. https://chat.openai.com/ Xpert Learning Assistant was used for troubleshooting errors for this project assignment.

- Xpert Learning Assistant. (2025). Retrieved from https://bootcampspot.instructure.com/
