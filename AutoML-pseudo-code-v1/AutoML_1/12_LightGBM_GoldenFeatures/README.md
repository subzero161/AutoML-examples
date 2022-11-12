# Summary of 12_LightGBM_GoldenFeatures

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.05
- **feature_fraction**: 0.9
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 20
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

102.2 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.984962 |   0.956835 |   0.984848 |   0.969697 |   0.963504 |   0.956204 |   0.970803 |   0.970588 |   0.952381 |   0.905797 |   0.961396 |    0.961562 |       0.961526 |  0.124281 |
| recall    |   0.984962 |   0.977941 |   0.977444 |   0.934307 |   0.970588 |   0.963235 |   0.977941 |   0.985075 |   0.916031 |   0.925926 |   0.961396 |    0.961345 |       0.961396 |  0.124281 |
| f1-score  |   0.984962 |   0.967273 |   0.981132 |   0.951673 |   0.967033 |   0.959707 |   0.974359 |   0.977778 |   0.933852 |   0.915751 |   0.961396 |    0.961352 |       0.96136  |  0.124281 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.961396 | 1347        |    1347        |  0.124281 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              131 |                0 |                0 |                0 |                1 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              133 |                0 |                0 |                1 |                0 |                1 |                0 |                0 |                1 |
| Labeled as 2 |                1 |                0 |              130 |                0 |                0 |                0 |                1 |                0 |                1 |                0 |
| Labeled as 3 |                0 |                1 |                0 |              128 |                0 |                4 |                0 |                0 |                2 |                2 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              132 |                0 |                1 |                0 |                0 |                3 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              131 |                1 |                0 |                0 |                4 |
| Labeled as 6 |                0 |                0 |                1 |                0 |                1 |                0 |              133 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                2 |                0 |                0 |              132 |                0 |                0 |
| Labeled as 8 |                1 |                3 |                1 |                2 |                0 |                0 |                0 |                1 |              120 |                3 |
| Labeled as 9 |                0 |                2 |                0 |                2 |                0 |                1 |                0 |                3 |                2 |              125 |

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
