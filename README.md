# Iris Flower Classification from Scratch (KNN with NumPy)

A from-scratch KNN classifier on the classic Iris dataset—no scikit-learn.  
**Final test accuracy:** ~96.7%

## What’s inside
- Data prep: encoding, stratified-ish split, standardization (no leakage)
- KNN (Euclidean distance, majority vote)
- Validation to choose best `k`
- Evaluation: confusion matrix, precision/recall/F1 (from scratch)

## Dataset
Uses the Iris dataset from Kaggle (uciml/iris).  
You can add it to a Kaggle notebook or download `Iris.csv`.

## Reproduce
```bash
pip install -r requirements.txt
# open the notebook and run cells
jupyter notebook iris_knn_from_scratch.ipynb
