# ML-HeartDisease
- `aggregation.ipynb`: aggregates original raw data from different hospitals `data/raw/hungarian.data`, `data/raw/long-beach-va.data
` and `data/raw/switzerland.data`. Generates `data/aggregated.csv` with column names.
- `preprocessing.ipynb`: performs data preprocessing and also displays graphs. Generates `data/train_data.csv` and `data/test_data.csv`
- `models.ipynb`: models trained on `data/train_data.csv` and compared through cross-validation. Best model found mainly considering f2-score and overall performance is Gradient Boosting.

# Authors
Roger Bargalló and Laia Mogas
