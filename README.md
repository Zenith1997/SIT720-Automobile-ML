# Automobile Price Regression and Classification

Use a small mixed-feature dataset to compare regression, regularization and binary classification.

**Python · pandas · scikit-learn · Ridge · Lasso · Logistic Regression**

## Project at a glance

The recorded test R² is 0.7383 for the initial linear model, 0.8546 for Ridge and 0.8926 for Lasso. L1 and L2 logistic models each report test accuracy 0.9268. These values come from the source experiment.

## Technical work

- Missing values, encoding and scaling
- Linear and logistic baselines
- Feature selection and regularization
- Regression and classification metrics

## Explore the evidence

- [SIT720_6.1P_Linear_Logistic_Regression.ipynb](SIT720_6.1P_Linear_Logistic_Regression.ipynb)
- [SIT720_6.1P_Report.pdf](SIT720_6.1P_Report.pdf)

## Run locally

```bash
python -m venv .venv
# Activate the environment, then:
python -m pip install jupyter numpy pandas matplotlib scikit-learn ucimlrepo
jupyter notebook
```

Follow the notebook's local_file setting or UCI-loading logic for Automobile data.

Open the linked notebook and run the cells in order. Package names reflect the source imports; a fresh environment was not tested during this documentation update. Dataset downloads require internet access.

## Limitations and status

UCI Automobile data contains only 205 records. LuxuryCar is a derived label, and feature-selection/threshold choices should be reviewed before interpreting classification scores as independent evidence.

The repository preserves saved notebook outputs. Results are from those outputs, not a new execution.

**Author:** Zenith Anthony Dabarera · SIT720 Machine Learning  
[AI/ML portfolio](https://github.com/Zenith1997)
