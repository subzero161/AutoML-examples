# Summary of 34_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.075
- **max_depth**: 4
- **min_child_weight**: 1
- **subsample**: 1.0
- **colsample_bytree**: 1.0
- **eval_metric**: mlogloss
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

103.5 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.970149 |   0.95     |   0.984962 |   0.970588 |   0.977612 |   0.963235 |   0.97037  |   0.956204 |   0.922481 |   0.924812 |   0.959169 |    0.959041 |       0.959133 |   0.13254 |
| recall    |   0.977444 |   0.977941 |   0.984962 |   0.963504 |   0.963235 |   0.963235 |   0.963235 |   0.977612 |   0.908397 |   0.911111 |   0.959169 |    0.959068 |       0.959169 |   0.13254 |
| f1-score  |   0.973783 |   0.963768 |   0.984962 |   0.967033 |   0.97037  |   0.963235 |   0.96679  |   0.96679  |   0.915385 |   0.91791  |   0.959169 |    0.959003 |       0.959099 |   0.13254 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.959169 | 1347        |    1347        |   0.13254 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                2 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              133 |                0 |                0 |                0 |                0 |                1 |                0 |                0 |                2 |
| Labeled as 2 |                1 |                0 |              131 |                0 |                0 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |              132 |                0 |                2 |                0 |                1 |                1 |                1 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              131 |                0 |                1 |                0 |                2 |                2 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              131 |                1 |                0 |                1 |                3 |
| Labeled as 6 |                1 |                1 |                0 |                0 |                0 |                1 |              131 |                0 |                2 |                0 |
| Labeled as 7 |                0 |                1 |                0 |                1 |                1 |                0 |                0 |              131 |                0 |                0 |
| Labeled as 8 |                1 |                4 |                1 |                2 |                0 |                0 |                0 |                2 |              119 |                2 |
| Labeled as 9 |                1 |                1 |                1 |                1 |                0 |                1 |                0 |                3 |                4 |              123 |

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
