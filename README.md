# Task 5: Decision Trees and Random Forests

## Overview
This project explores tree-based machine learning models for classification using a Heart Disease dataset. A Decision Tree Classifier and a Random Forest Classifier are trained and evaluated using Scikit-learn.

## Objectives
- Train and visualize a Decision Tree Classifier.
- Analyze overfitting and the effect of maximum tree depth.
- Train a Random Forest Classifier and compare its performance with the Decision Tree.
- Identify important features using Random Forest feature importance.
- Evaluate model performance using 5-fold cross-validation.

## Dataset
- **File:** `heart.csv`
- **Original records:** 1,025
- **Features:** 13 input features
- **Target:** `target`

The dataset was inspected for missing values and duplicate records. Duplicate rows were removed before the final model evaluation, leaving 302 unique records.

## Methodology
1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Remove duplicate rows.
4. Split the cleaned dataset into training and testing sets using an 80:20 ratio.
5. Train and evaluate a Decision Tree Classifier.
6. Visualize the tree and compare different maximum-depth settings.
7. Train and evaluate a Random Forest Classifier.
8. Compare both models on the same test set.
9. Analyze Random Forest feature importance.
10. Evaluate the Random Forest using 5-fold cross-validation.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Cross-validation accuracy

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Files
- `Task_5_Decision_Trees_Random_Forests.ipynb` — notebook containing the code, visualizations, and evaluation.
- `heart.csv` — dataset used in the project.

## Conclusion
This project compares Decision Tree and Random Forest classifiers, examines overfitting, and investigates feature importance and cross-validation performance. The results are documented in the notebook.

**Note:** This is an educational machine learning project. Predictions from this dataset are not intended for medical diagnosis.
