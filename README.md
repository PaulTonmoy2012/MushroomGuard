# MushroomGuard

This project applies machine learning on the Mushroom dataset to classify samples as edible or poisonous.

## Short Description
An end-to-end classification project that compares Decision Tree, Logistic Regression, and KNN models for mushroom safety prediction, then explains model decisions using LIME and SHAP.

## What is included
- Data preprocessing with random missing-value injection and cleaning
- Label encoding and MinMax feature scaling
- Model training and comparison: Decision Tree, Logistic Regression, and KNN
- Evaluation using accuracy, precision, recall, and confusion matrices
- Explainability experiments using LIME and SHAP

## Main file
- CSE422_Lab_Final_Project.ipynb

## Note
The notebook currently uses an absolute local path for the dataset. For GitHub portability, replace it with a relative path such as `mushrooms.csv` and keep the CSV in the repository root.
