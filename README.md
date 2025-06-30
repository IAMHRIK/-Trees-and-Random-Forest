# Task 5: Decision Trees & Random Forests on Breast Cancer Dataset

## Objective
Train Decision Tree and Random Forest models on the Breast Cancer dataset. Visualize the tree, analyze overfitting, and interpret feature importances.

## Dataset
- scikit-learn's built-in Breast Cancer dataset
- 30 features, binary classification (malignant/benign)

## Tasks Done
 Trained a Decision Tree (max_depth=5)  
 Saved tree visualization as PDF  
 Tested overfitting by trying depths: 3, 5, 10, None  
 Trained Random Forest (100 trees, max_depth=5)  
 Compared accuracy of Decision Tree vs Random Forest  
 Displayed top features by importance  
 Plotted depth vs accuracy  
 Ran 5-fold cross-validation on Random Forest  
 
## Results
- Random Forest outperformed Decision Tree in accuracy and stability
- Top features: worst perimeter, mean perimeter, worst radius, etc.
