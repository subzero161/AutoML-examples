# Summary of 6_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: multi:softprob
- **eta**: 0.075
- **max_depth**: 8
- **min_child_weight**: 5
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

54.1 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.970149 |   0.90411  |   0.984733 |   0.963235 |   0.948148 |   0.962687 |   0.956522 |   0.977099 |   0.921875 |   0.925373 |   0.951002 |    0.951393 |       0.951377 |  0.167262 |
| recall    |   0.977444 |   0.970588 |   0.969925 |   0.956204 |   0.941176 |   0.948529 |   0.970588 |   0.955224 |   0.900763 |   0.918519 |   0.951002 |    0.950896 |       0.951002 |  0.167262 |
| f1-score  |   0.973783 |   0.93617  |   0.977273 |   0.959707 |   0.944649 |   0.955556 |   0.963504 |   0.966038 |   0.911197 |   0.921933 |   0.951002 |    0.950981 |       0.951025 |  0.167262 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.951002 | 1347        |    1347        |  0.167262 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                2 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              132 |                0 |                0 |                1 |                0 |                1 |                0 |                0 |                2 |
| Labeled as 2 |                1 |                1 |              129 |                1 |                0 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                1 |                1 |              131 |                0 |                2 |                0 |                1 |                1 |                0 |
| Labeled as 4 |                1 |                0 |                0 |                0 |              128 |                0 |                3 |                0 |                3 |                1 |
| Labeled as 5 |                0 |                0 |                0 |                1 |                0 |              129 |                1 |                0 |                1 |                4 |
| Labeled as 6 |                0 |                2 |                0 |                0 |                1 |                0 |              132 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                1 |                0 |                0 |                3 |                0 |                0 |              128 |                1 |                1 |
| Labeled as 8 |                1 |                5 |                1 |                1 |                0 |                1 |                0 |                2 |              118 |                2 |
| Labeled as 9 |                1 |                4 |                0 |                2 |                0 |                1 |                0 |                0 |                3 |              124 |

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
