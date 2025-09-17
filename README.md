# breast-cancer-ml-demo
Mini-project on AI applied to clinical data (Breast Cancer Wisconsin)

## What this does
Trains and evaluates two models (Logistic Regression and Random Forest) to classify benign vs malignant tumors using a public scikit-learn dataset.

## How to run (Google Colab)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook (`.ipynb`)
3. Click **Connect** → **Runtime → Run all**
4. It will generate `modelo_rf_breast_cancer.joblib` (optional download)

## Results (my run)
- Logistic Regression: ROC-AUC = **0.996**
- Random Forest: ROC-AUC = **0.994**
- Top features: see table and bar chart in the notebook

## Notes
Educational project with public data; **not** for real clinical use.
