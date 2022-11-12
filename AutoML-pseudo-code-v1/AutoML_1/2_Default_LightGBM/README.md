# Summary of 2_Default_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 63
- **learning_rate**: 0.05
- **feature_fraction**: 0.9
- **bagging_fraction**: 0.9
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

122.5 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.970149 |   0.950704 |   0.992366 |   0.970803 |   0.977778 |   0.970588 |   0.977778 |   0.963768 |   0.968254 |   0.93985  |   0.968077 |    0.968204 |       0.968175 |  0.119508 |
| recall    |   0.977444 |   0.992647 |   0.977444 |   0.970803 |   0.970588 |   0.970588 |   0.970588 |   0.992537 |   0.931298 |   0.925926 |   0.968077 |    0.967986 |       0.968077 |  0.119508 |
| f1-score  |   0.973783 |   0.971223 |   0.984848 |   0.970803 |   0.97417  |   0.970588 |   0.97417  |   0.977941 |   0.949416 |   0.932836 |   0.968077 |    0.967978 |       0.96801  |  0.119508 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.968077 | 1347        |    1347        |  0.119508 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                2 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              135 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |                1 |
| Labeled as 2 |                1 |                0 |              130 |                1 |                0 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |              133 |                0 |                2 |                0 |                2 |                0 |                0 |
| Labeled as 4 |                0 |                1 |                0 |                0 |              132 |                0 |                1 |                0 |                0 |                2 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              132 |                1 |                0 |                0 |                3 |
| Labeled as 6 |                1 |                1 |                0 |                0 |                0 |                1 |              132 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                1 |                0 |                0 |              133 |                0 |                0 |
| Labeled as 8 |                1 |                3 |                1 |                1 |                0 |                0 |                0 |                1 |              122 |                2 |
| Labeled as 9 |                1 |                2 |                0 |                2 |                0 |                0 |                0 |                2 |                3 |              125 |

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
