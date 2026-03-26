# Assignment-1
Lecture 1 COMPAS workflow reproduced in Python
# COMPAS Analysis in Python (Lecture 1)

## Overview
This project reproduces the COMPAS workflow from Lecture 1 using Python. The goal is to translate the original R-based analysis into a fully reproducible Python workflow, including data cleaning, exploratory data analysis (EDA), logistic regression modeling, and fairness checks.

## Dataset
The dataset used in this analysis is the COMPAS dataset from ProPublica. It is loaded directly from the public GitHub source.

## Methods
The analysis follows the same steps as Lecture 1:

- Data cleaning and filtering
- Feature engineering and variable creation
- Exploratory data analysis (EDA)
- Logistic regression modeling
- Prediction and classification
- Model evaluation using confusion matrix and metrics
- Fairness analysis by race (FPR, FNR, disparities)

## Key Findings
The model performs reasonably well overall, with moderate accuracy and precision. However, fairness analysis shows that error rates differ across racial groups. In particular, the false positive rate is significantly higher for African-American defendants compared to Caucasian defendants.

This highlights the key takeaway from Lecture 1: a model can appear accurate overall while still producing unequal outcomes across groups.

## How to Run
1. Open the notebook file (`.ipynb`)
2. Run all cells from top to bottom
3. The dataset is loaded automatically from GitHub (no manual download required)

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn

## Notes
Following the Lecture 1 setup, the model predicts COMPAS risk scores while evaluation is done using actual two-year recidivism outcomes. This reflects the lecture’s focus on comparing predicted risk to real-world outcomes.
