# Medical Insurance Charges Prediction

## Overview

This project aims to predict individual medical insurance charges using a dataset that includes features such as age, BMI, smoking status, and region. The project involves building and evaluating machine learning models to predict insurance charges and performing exploratory data analysis (EDA) to understand the factors influencing these charges.

## Objectives

1. **Understand the Data**: Analyze the dataset to comprehend its features and the target variable.
2. **Exploratory Data Analysis (EDA)**: Use visualizations to explore and interpret the relationships between features and charges.
3. **Predictive Modeling**: Develop and evaluate machine learning models to predict insurance charges.
4. **Reporting**: Generate an HTML report summarizing the findings and visualizations from the EDA.
5. **Version Control**: Instructions for uploading the report to GitHub.

## Dataset

The dataset contains the following columns:

- **age**: Age of the primary beneficiary.
- **sex**: Gender of the insurance contractor (female, male).
- **bmi**: Body Mass Index, a measure of body fat based on height and weight.
- **children**: Number of children/dependents covered by health insurance.
- **smoker**: Smoking status (yes, no).
- **region**: Residential area in the US (northeast, southeast, southwest, northwest).
- **charges**: Individual medical costs billed by health insurance.

## Installation

To run the code, ensure you have the following Python libraries installed:

`bash
pip install pandas numpy seaborn matplotlib scikit-learn

## Usage

### Data Preparation

1. **Load the Dataset**: Import the dataset using pandas.
2. **Encode Categorical Variables**: Convert categorical features (`sex`, `smoker`, `region`) into numerical values using one-hot encoding.
3. **Split the Data**: Divide the dataset into training and test sets using `train_test_split` from `sklearn`.

### Exploratory Data Analysis (EDA)

1. **Visualize Distributions**: Use `seaborn` and `matplotlib` to create visualizations of the distribution of insurance charges.
2. **Analyze Relationships**:
   - Plot charges versus age.
   - Plot charges versus BMI.
   - Compare charges by smoker status.

### Model Building

1. **Train a Linear Regression Model**:
   - Fit the model on the training set.
   - Predict charges on the test set.
2. **Train a Random Forest Regressor Model**:
   - Fit the model on the training set.
   - Predict charges on the test set.
3. **Evaluate Both Models**:
   - **Mean Absolute Error (MAE)**: Measures the average magnitude of errors.
   - **Root Mean Squared Error (RMSE)**: Measures the square root of the average squared errors.
   - **R-squared**: Indicates the proportion of variance explained by the model.

### Generate Report

1. **Create an HTML Report**:
   - Include visualizations and insights from the EDA.
   - Save the report as `Medical_Analysis_Report.html`.

### Upload to GitHub

1. **Create a New Repository**:
   - Go to GitHub and create a new repository.
2. **Upload the HTML Report**:
   - Add the `Medical_Analysis_Report.html` file to the repository.
3. **Commit and Push**:
   - Commit and push your changes to the repository.

## Results

### Linear Regression

- **Mean Absolute Error (MAE)**: `4181.194473753649`  
- **Root Mean Squared Error (RMSE)**: `5796.284659276272`  
- **R-squared (R^2)**: `0.7835929767120724`  

### Random Forest Regressor

- **Mean Absolute Error (MAE)**: `2550.0784706115096`  
- **Root Mean Squared Error (RMSE)**: `4576.299916157115`  
- **R-squared (R^2)**: `0.8651034329144947`  

