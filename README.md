# Exam Score Prediction

Machine learning project that predicts student **exam scores** from study habits and academic features.

## Pipeline

1. **Preprocessing** - Missing values / duplicates checks, feature selection, categorical encoding, outlier clipping, scaling
2. **Models** - Linear & polynomial regression, SVR, Decision Tree, Random Forest, XGBoost, HistGradientBoosting, Stacking
3. **Evaluation** - RMSE / R² on a held-out validation split, plus residual plots
4. **Submission** - Predictions exported as `sample_submission_*.csv`

## Data

| File                    | Role                                        |
| ----------------------- | ------------------------------------------- |
| `train.csv`             | Labeled training data (`exam_score` target) |
| `test.csv`              | Unlabeled test set for final predictions    |
| `sample_submission.csv` | Submission template (`id`, `exam_score`)    |

Features include study hours, attendance, sleep, course, study method, facility rating, and related fields.

## Notebook

`Notebook.ipynb` contains the full pipeline. Outputs, metrics, plots, and trained-model results are already cached in the notebook.
