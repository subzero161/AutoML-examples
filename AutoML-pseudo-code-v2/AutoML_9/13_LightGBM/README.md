# Summary of 13_LightGBM

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: multiclass
- **num_leaves**: 95
- **learning_rate**: 0.05
- **feature_fraction**: 1.0
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

75.0 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.97037  |   0.937063 |   0.992188 |   0.949275 |   0.984962 |   0.956522 |   0.977778 |   0.970803 |   0.96748  |   0.919708 |   0.962138 |    0.962615 |       0.962523 |     0.132 |
| recall    |   0.984962 |   0.985294 |   0.954887 |   0.956204 |   0.963235 |   0.970588 |   0.970588 |   0.992537 |   0.908397 |   0.933333 |   0.962138 |    0.962003 |       0.962138 |     0.132 |
| f1-score  |   0.977612 |   0.960573 |   0.97318  |   0.952727 |   0.973978 |   0.963504 |   0.97417  |   0.98155  |   0.937008 |   0.926471 |   0.962138 |    0.962077 |       0.962102 |     0.132 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.962138 | 1347        |    1347        |     0.132 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              131 |                0 |                0 |                0 |                1 |                1 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              134 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |                2 |
| Labeled as 2 |                1 |                1 |              127 |                3 |                0 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                1 |                0 |              131 |                0 |                2 |                0 |                1 |                1 |                1 |
| Labeled as 4 |                0 |                1 |                0 |                0 |              131 |                0 |                1 |                0 |                0 |                3 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              132 |                1 |                0 |                0 |                3 |
| Labeled as 6 |                1 |                1 |                0 |                0 |                0 |                1 |              132 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                1 |                0 |                0 |              133 |                0 |                0 |
| Labeled as 8 |                1 |                3 |                1 |                3 |                0 |                1 |                0 |                1 |              119 |                2 |
| Labeled as 9 |                1 |                2 |                0 |                1 |                0 |                1 |                0 |                2 |                2 |              126 |

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
