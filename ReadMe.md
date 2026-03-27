# Diabetes Prediction – Deep Learning Project

## Overview

This project aims to develop a machine learning and deep learning model capable of predicting whether an individual is likely to have diabetes based on a set of health-related indicators.

The dataset used comes from the Behavioral Risk Factor Surveillance System (BRFSS), a large-scale health survey conducted in the United States. It contains more than 250,000 observations and multiple variables describing medical conditions, lifestyle habits, and socio-demographic factors.

This work is part of a Problem-Based Learning (PBL) approach, where the objective is not only to build a predictive model but also to understand the entire data science pipeline, from data preparation to model evaluation.

---

## Objectives

The main objective of this project is to build a binary classification model that predicts the presence of diabetes using health indicators.

More specifically, the project aims to:

- Understand and explore the dataset
- Prepare and clean the data
- Identify relevant features
- Train and evaluate machine learning and deep learning models
- Optimize model performance using appropriate metrics such as ROC AUC
- Reflect on model limitations and potential improvements

---

## Dataset

The dataset used is based on the BRFSS 2015 survey and includes:

- 253,680 observations
- 22 variables

The target variable is:

- `Diabetes_binary`:
  - 0: no diabetes
  - 1: diabetes

The features include various health and lifestyle indicators such as BMI, blood pressure, cholesterol levels, physical activity, smoking habits, and general health.

---

## Project Structure

The project is organized as follows:

Projet/
- diabetes_binary_health_indicators_BRFSS2015.csv
- livrable1_pretraitement.ipynb
- train_clean.csv
- val_clean.csv
- test_clean.csv
- README.md
- `livrable1_pretraitement.ipynb`: notebook containing all preprocessing steps
- `train_clean.csv`, `val_clean.csv`, `test_clean.csv`: cleaned and split datasets ready for modeling

---

## Work Completed – Livrable 1 (Data Preparation)

The first stage of the project focused on preparing the dataset for modeling. The following steps were carried out:

- Initial loading and understanding of the dataset
- Identification of the target variable and feature variables
- Typing of variables (binary, ordinal, numerical)
- Detection and removal of duplicate rows
- Verification of missing values
- Exploratory data analysis (statistical and visual)
- Analysis of outliers, especially on the BMI variable
- Train / validation / test split with stratification
- Definition of a normalization strategy (StandardScaler)
- Export of cleaned datasets for further use

This stage ensured that the data is reliable, consistent, and ready for machine learning.

---

## Methodological Choices

Several important methodological decisions were made during this stage:

- Duplicate rows were removed to avoid over-representation of identical profiles
- Outliers were identified but not removed to preserve potentially meaningful information
- No missing values were detected, so no imputation was required
- Stratified splitting was used to maintain class balance across datasets
- StandardScaler was selected as a reference normalization method for future modeling

These choices were made to ensure both data quality and methodological rigor.

---

## Next Steps

The next stages of the project will focus on model development and evaluation. Planned tasks include:

- Development of a deep learning model (neural network)
- Application of normalization techniques where required
- Handling class imbalance if necessary
- Model evaluation using appropriate metrics (ROC AUC)
- Hyperparameter tuning and model optimization
- Interpretation of results and identification of key predictive features

If relevant, simpler models may be explored for comparison purposes.
---

## Collaboration

This project is managed using GitHub to enable collaboration between team members. Each contributor can work on different parts of the project, track changes, and maintain a consistent workflow.

---

## Conclusion

This first stage provides a solid foundation for the rest of the project. By carefully preparing and understanding the data, we ensure that future modeling steps are built on reliable and well-structured inputs.

The following phases will focus on transforming this prepared data into a performant and interpretable predictive model.
