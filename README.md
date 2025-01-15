# Credit Score Classification

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting_started)
3. [Project Imports & Requirement](#project_imports_&_requirement)
4. [Project Contents](#project_contents)
5. [Project Overview](#project_overview)
6. [Contributers](#contributers)
7. [References](#references)

## Introduction
This project analyzes financial data to understand and predict the factors that determine credit scores, such as loan interest rates, credit mix, credit history, and unusual patterns or outliers in these variables. Using Jupyter Notebook, we clean, prepare, and standardize the dataset before analyzing it with machine learning models, including Logistic Regression, Neural Networks, Decision Trees, Gradient Boosting, and Random Forest. The primary goal of this project is to develop a machine learning system that predicts an individual’s credit score category (Good, Standard, or Poor) based on their financial and credit-related information. This system aims to streamline the classification process, reduce manual efforts, and provide accurate insights into creditworthiness, helping financial institutions make informed decisions.

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
6. Requirements: Python Matplotlib and Python Pandas

### Requirements
- [Powerpoint Presentation](https://docs.google.com/presentation/d/1KzKBNVX8u-9dERdYQd39QQngYujC3KZzNRr9a3HlKCM/edit?usp=sharing)

## Project Contents 
1. **Resources Folder**:
   - Contains our raw datasets (_'test.csv'_ and _'train.csv'_) and our cleaned dataset with (_'test_cleaned.csv'_ and _'train_cleaned.csv'_) and without outliers (_'test_cleaned_without_outliers.csv'_ and _'train_cleaned_without_outliers.csv'_). 
2. **Jupyter Notebooks**:
   - **main_analysis.ipynb**2: The primary notebook where data cleaning and preparing took place.
   - **heatmap_&_histogram_graph.ipynb**: Contains graphs and visual using matplotlib to better understand the dataset and communicate to audience during presentation.
   - **Machine_Learning_Models.ipynb**: Focuses on cleaned dataset analysis using machine learning models--implemented through Random Forest, Gradient Boosting, & Decision Trees.
   - **'LR and NN Model' Folder - 'Logistic_Regression_code.ipynb' & 'NN_Model_code.ipynb'**: Focuses on cleaned dataset analysis using machine learning models--implemented through Logistic Regression and Neural Network Model.
3. **RF_GB_DT_Figures** Folder - Output of graph visuals from 'Machine_Learning_Models.ipynb'
4. Presentation: PowerPoint Summarizing the project, key insights, results. 
5. README.md

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
- [Dylon Wilson](https://github.com/dwilson1821)
- [Jana Naum](https://github.com/jananaum7)


## References

ChatGPT and Xpert Learning Assistant were used for analysis reference and troubleshooting errors for this project assignment.

- MoneyMan. (2020). Credit card approval prediction. Kaggle. https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction 
- OpenAI. (January, 2025). ChatGPT (GPT-4) [Large language model]. https://chat.openai.com/ Xpert Learning Assistant was used for troubleshooting errors for this project assignment.
- Paris, R. (2022, June 22). Credit Score Classification. Kaggle. https://www.kaggle.com/datasets/parisrohan/credit-score-classification?resource=download&select=train.csv 
- Rikdifos, M. (2021, July 14). Eda & Vintage Analysis. Kaggle. https://www.kaggle.com/code/rikdifos/eda-vintage-analysis 
- Xpert Learning Assistant. (2025). Retrieved from https://bootcampspot.instructure.com/
