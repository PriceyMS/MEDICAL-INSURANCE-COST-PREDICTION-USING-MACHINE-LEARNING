# MEDICAL-INSURANCE-COST-PREDICTION-USING-MACHINE-LEARNING

## Overview
This project applies machine learning techniques to predict medical insurance charges based on individual demographic and lifestyle factors. It demonstrates a complete regression workflow, from data preprocessing and exploratory analysis to model training and evaluation, using a real-world healthcare dataset.

The project highlights how data-driven models can be used to estimate healthcare costs and identify key factors influencing insurance pricing.

## Dataset
The dataset contains information about insured individuals with the following features:

- Age
- Sex
- Body Mass Index (BMI)
- Number of children/dependents
- Smoking status
- Region
- Medical insurance charges (target variable)

## Project Workflow

### 1. Data Exploration
- Examined dataset structure and feature distributions  
- Identified relationships between variables and insurance charges  
- Observed significant cost differences associated with smoking status  

### 2. Data Preprocessing
- Encoded categorical variables
- Scaled numerical features where necessary
- Split data into training and testing sets

### 3. Model Training
- Built regression models to predict insurance costs
- Trained models on historical insurance data
- Optimized performance using appropriate preprocessing steps

### 4. Model Evaluation
- Evaluated predictions against actual insurance charges
- Assessed model performance using regression metrics
- Analyzed feature influence on predicted costs

## Key Insights
- Smoking status is a major driver of higher insurance charges
- Age and BMI significantly influence medical costs
- Machine learning models can effectively capture cost patterns in healthcare data


## Tools and Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  


## Future Improvements
- Apply advanced regression models such as Random Forest and Gradient Boosting
- Perform hyperparameter tuning for improved accuracy
- Deploy the model as a web application for real-time predictions


## Author
Developed as a machine learning portfolio project focused on healthcare cost prediction and applied data science.
