# X-LIRM

## Overview

X-LIRM is an Explainable LLM-Inspired Reasoning-Based Meta-Learning Framework for Liver Disease Prediction.

The framework integrates:
- Recursive Feature Elimination (RFE)
- SHAP Explainability
- Random Forest Feature Importance
- Meta-Learning Based Ensemble Classification

The proposed framework improves predictive performance and interpretability for liver disease diagnosis.

---

## Dataset

Indian Liver Patient Dataset (ILPD)

Dataset Link:
https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset

---

## Methodology

The proposed pipeline consists of:

1. Data Preprocessing
2. SMOTE Class Balancing
3. Recursive Feature Elimination (RFE)
4. SHAP + Random Forest Feature Refinement
5. Training RF, XGBoost, and SVM
6. Confidence-Aware Meta Learning
7. Final Liver Disease Prediction

---

## Results

| Metric | Value |
|---|---|
| Accuracy | 81.37% |
| Precision | 79.86% |
| Recall | 91.30% |
| F1-Score | 82.25% |
| Specificity | 79.44% |
| AUC | 0.8898 |

---

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Imbalanced-learn

---

## Run

```bash
pip install -r requirements.txt
jupyter notebook
```
