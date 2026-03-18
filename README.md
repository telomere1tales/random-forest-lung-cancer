# Random Forest Classification - Lung Cancer Prediction

## Overview
This project builds a Random Forest classification model to predict 
lung cancer status from clinical symptoms and lifestyle factors using 
a survey-based dataset of 309 patients.

## Methods
- **Data preprocessing:** variable conversion, normalization and scaling
- **Class imbalance handling** using class weights (NO = 10, YES = 1)
- **Random Forest** classification with 500 trees and mtry = 4
- **Model evaluation:** confusion matrix, sensitivity, specificity, AUC-ROC
- **Variable importance** analysis using the `vip` package

## Key Findings
- AUC-ROC = 0.966 (outstanding discriminative ability)
- Sensitivity = 98.1% (critical for screening tool)
- Alcohol consuming, peer pressure and yellow fingers were the 
strongest predictors
- Age and Gender showed the lowest importance

## Tools & Packages
- R 4.5.3
- `randomForest`, `caret`, `pROC`, `vip`, `corrplot`, `tidyverse`

## Files
- `random_forest_lung_cancer.Rmd` — R Markdown source code
- `random_forest_lung_cancer.html` — Full rendered report
