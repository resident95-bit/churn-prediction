# Customer Churn Prediction

Train a random forest to predict customer churn using a reproducible synthetic dataset.
The script reports evaluation metrics from a test split.

## Run

```sh
python -m pip install -r requirements.txt
python train.py
```

Python 3.13 is used in CI. The dataset contains 2,000 rows and 12 features, with
an imbalanced target representing customers who stay or churn.

## Continuous integration

GitHub Actions installs the dependencies and runs the training script on pushes
and pull requests.
