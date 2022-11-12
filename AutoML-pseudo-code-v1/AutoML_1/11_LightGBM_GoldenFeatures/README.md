# Summary of 11_LightGBM_GoldenFeatures

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.2
- **feature_fraction**: 0.5
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 10
- **metric**: multi_logloss
- **custom_eval_metric_name**: None
- **num_class**: 10
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

40.8 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.984848 |   0.957746 |   1        |   0.970149 |   0.970588 |   0.970588 |   0.992537 |   0.963768 |   0.960938 |   0.933824 |   0.970304 |    0.970499 |       0.970474 | 0.0939664 |
| recall    |   0.977444 |   1        |   0.984962 |   0.948905 |   0.970588 |   0.970588 |   0.977941 |   0.992537 |   0.938931 |   0.940741 |   0.970304 |    0.970264 |       0.970304 | 0.0939664 |
| f1-score  |   0.981132 |   0.978417 |   0.992424 |   0.95941  |   0.970588 |   0.970588 |   0.985185 |   0.977941 |   0.949807 |   0.937269 |   0.970304 |    0.970276 |       0.970284 | 0.0939664 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.970304 | 1347        |    1347        | 0.0939664 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                2 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              136 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 2 |                1 |                0 |              131 |                1 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                1 |                0 |              130 |                0 |                3 |                0 |                1 |                1 |                1 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              132 |                0 |                0 |                1 |                1 |                2 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              132 |                1 |                0 |                0 |                3 |
| Labeled as 6 |                0 |                1 |                0 |                0 |                1 |                0 |              133 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                1 |                0 |                0 |              133 |                0 |                0 |
| Labeled as 8 |                0 |                3 |                0 |                1 |                0 |                0 |                0 |                1 |              123 |                3 |
| Labeled as 9 |                1 |                1 |                0 |                2 |                0 |                0 |                0 |                2 |                2 |              127 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
