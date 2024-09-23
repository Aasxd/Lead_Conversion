# Lead Conversion Prediction

This repository contains the analysis and modeling for predicting lead conversion using logistic regression.

## Project Overview

The goal of this project is to predict the likelihood of lead conversion based on various features using logistic regression. The dataset used includes information about leads, their interactions, and other related attributes.

## Files Included

- `LeadScoringAssignment.py`: Contains the Python script for data analysis, model building, and evaluation.
- `Summary_of_LSA.pdf`: A document detailing the data quality check, preprocessing steps, insights and recommendations.
- `LeadScoringAssignmentPPT.pdf`: A presentation summarizing the analysis and results.
- `Assignment_Subjective_Q.pdf`: A document that answers the subjective questions related to the data analysis.


## Data Preparation

- Missing values were handled by imputation and dropping columns with excessive missing data.
- Categorical variables were converted to dummy variables.
- Numerical features were scaled to ensure fair contribution to the model.

## Model Building

- A logistic regression model was used for predicting lead conversion.
- The model was evaluated using metrics such as accuracy, precision, recall, and F1 score.

## Results

- The model achieved an accuracy of 85.1%, precision of 82.2%, recall of 77.2%, and an F1 score of 79.6%.