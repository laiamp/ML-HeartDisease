# ML-HeartDisease
- `aggregation.ipynb`: aggregates original raw data from different hospitals `data/raw/hungarian.data`, `data/raw/long-beach-va.data
` and `data/raw/switzerland.data`. Generates `data/aggregated.csv` with column names.
- `preprocessing.ipynb`: performs data preprocessing and also displays graphs. Generates `data/train_data.csv` and `data/test_data.csv`
- `models.ipynb`: models trained on `data/train_data.csv` and compared through cross-validation. Best model found mainly considering f2-score and overall performance is Gradient Boosting.

# Dataset
The dataset used is [Heart Disease Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease), published on 06/30/1988. It consists of data from four medical centers in Europe and the United States:


    - Cleveland Clinic Foundation (cleveland.data)
    - Hungarian Institute of Cardiology, Budapest (hungarian.data)
    - V.A. Medical Center, Long Beach, CA (long-beach-va.data)
     - University Hospital, Zurich, Switzerland (switzerland.data)


As cleveland.data was corrupted and only a processed version of it can be found online, we limited our analysis to the remaiining three medical centers. Since all the datasets contain the same 76 variables, we combined the remaining three datasets into one.

# Authors
Roger Bargalló and Laia Mogas
