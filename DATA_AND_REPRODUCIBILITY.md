# Dataset and reproducibility notes

The notebook uses **UCI Automobile**, accessed with `ucimlrepo.fetch_ucirepo(id=10)` or local `automobiles_uci_equiv.csv`/`automobile.csv`. The original source has only 205 rows.

It contains a regression target (`price`) and a **derived** classification label (`LuxuryCar`); inspect how that label is constructed before treating binary accuracy as externally validated. Avoid carrying any variable used to *define* the label into an input predictor.

Data and permissions should be obtained directly from UCI. The static CI only validates the notebook JSON, not the model's recorded metrics.

## Running the original notebook

```bash
python -m pip install -r requirements.txt
jupyter notebook SIT720_6.1P_Linear_Logistic_Regression.ipynb
```

These are version *ranges*, not an exact captured original environment. A fresh run has not been validated by this documentation update.
