# Iris Flower Classification from Scratch (KNN with NumPy)

A from-scratch implementation of the **K-Nearest Neighbors (KNN)** classifier on the classic **Iris dataset**, built entirely with **NumPy + Pandas**, without scikit-learn.  

This project demonstrates:
- Data preprocessing (encoding labels, standardizing features without data leakage)
- Implementing KNN manually (Euclidean distance, majority voting)
- Model selection (finding best `k` via validation)
- Deep evaluation (confusion matrix, precision, recall, F1-score)

---

## Results

**Best k:** 7  
**Final test accuracy:** **96.7%**

### Per-Class Metrics
| Class       | Precision | Recall | F1-score |
|-------------|-----------|--------|----------|
| Setosa      | 1.000     | 1.000  | 1.000    |
| Versicolor  | 0.900     | 1.000  | 0.947    |
| Virginica   | 1.000     | 0.923  | 0.960    |

### Overall Averages
| Average Type | Precision | Recall | F1-score |
|--------------|-----------|--------|----------|
| **Macro**    | 0.967     | 0.974  | 0.969    |
| **Micro**    | 0.967     | 0.967  | 0.967    |

---
