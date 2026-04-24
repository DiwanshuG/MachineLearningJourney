# Day 76 - Optuna Tuning and Imbalanced Data in ML

This mini-project explores practical model improvement workflows for tabular machine learning, including hyperparameter tuning with Optuna and robust handling of imbalanced datasets.

## Repository Contents

- `PIMA_Optuna_XGboost.ipynb`  
  End-to-end diabetes classification pipeline: data loading, preprocessing, Optuna optimization, XGBoost training, and ROC-AUC evaluation.

- `HyperParameterTuningUsingOptuna.ipynb`  
  Detailed Optuna tutorial covering core concepts, sampler strategies (TPE, Random, Grid), visual diagnostics, and an Optuna + XGBoost pipeline.

- `ImbalanceDataInML.ipynb`  
  Structured walkthrough of imbalanced classification: baseline pitfalls, undersampling, oversampling, SMOTE, class-weight methods, ensemble methods, and custom-loss-based cost-sensitive learning.

## Notebook Highlights

1. `PIMA_Optuna_XGboost.ipynb`
- Clear objective and workflow documentation
- Optuna pruning with XGBoost
- Generalization-focused recommendations

2. `HyperParameterTuningUsingOptuna.ipynb`
- Concept-to-code Optuna learning path
- Sampler comparison and interpretation
- Visualization-based hyperparameter analysis

3. `ImbalanceDataInML.ipynb`
- Why accuracy can be misleading on imbalanced data
- Side-by-side technique comparison (under/over/SMOTE/ensemble/class-weight/custom loss)
- Practical guidance for choosing methods based on error-cost tradeoffs

## Key Workflow in PIMA Notebook

1. Load and clean the dataset
2. Split data into train/validation/test sets (60/20/20)
3. Optimize XGBoost parameters with Optuna + pruning
4. Train final model with best parameters
5. Evaluate using ROC-AUC

## Run Locally

```bash
pip install -U optuna xgboost numpy pandas scikit-learn jupyter
jupyter notebook
```

Or install from the included requirements file:

```bash
pip install -r requirements.txt
```

Open the notebook(s) and run cells top-to-bottom.

## Notes

- Random seed is controlled in train/validation/test splitting (`random_state=42`) for reproducibility.
- The PIMA notebook includes overfitting diagnosis and concrete next-step improvements.
- The imbalance notebook now uses cleaner, sectioned markdown commentary for better readability on GitHub.

## Suggested Next Improvements

- Replace single validation split with Stratified K-Fold cross-validation in Optuna objective
- Tune `scale_pos_weight` explicitly for imbalance
- Increase number of Optuna trials
- Add a final consolidated comparison table across all notebooks with a single evaluation protocol
