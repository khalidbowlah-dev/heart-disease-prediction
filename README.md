# Heart Disease Prediction Model

## Overview
This repository contains a machine learning pipeline developed to predict the presence of heart disease in patients. The project demonstrates an end-to-end data science workflow, including data preprocessing, model training, and visual performance evaluation.

## Dataset
The analysis utilizes the Cleveland Heart Disease dataset. Initial data cleaning involved identifying and removing rows with missing values to ensure robust model training.

## Methodology & Tools
* **Language:** Python
* **Libraries:** pandas, scikit-learn, matplotlib, seaborn
* **Model:** A Random Forest Classifier was selected for its strong predictive accuracy and ability to interpret feature importance. The data was divided into an 80% training set and a 20% testing set.

## Results
* The Random Forest model achieved a testing accuracy of 88.33%.
* Evaluation through a confusion matrix confirmed high precision and recall across classifications.
* Feature importance analysis revealed that `thalach` (maximum heart rate achieved) and `ca` (number of major vessels) were the most significant predictors of heart disease in this dataset.
