# knn-iris-hyperparameter-tuning
# Ex 15.8 — KNN Classification with Hyperparameter Tuning on Iris Dataset

This project implements KNN classification on the Iris dataset with hyperparameter tuning.

## Steps
1. Load Iris dataset from sklearn.
2. Perform 10-fold cross-validation for K=1..31.
3. Plot:
   - Value of K vs Cross-Validated Accuracy (1..31)
   - Zoomed-in plot around optimal K
4. Confirm optimal K using GridSearchCV.

## Results
- Best K = 13
- Best mean CV accuracy = 0.98
- Confirmed with GridSearchCV.

## How to run
```bash
jupyter notebook EX15_8_KNN_Iris_Hyperparameter_Tuning.ipynb
