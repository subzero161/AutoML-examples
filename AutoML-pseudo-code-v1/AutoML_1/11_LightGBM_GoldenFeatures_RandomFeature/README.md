# Summary of 11_LightGBM_GoldenFeatures_RandomFeature

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

35.6 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.977612 |   0.944056 |   0.985075 |   0.963235 |   0.97037  |   0.970149 |   0.977612 |   0.970588 |   0.967742 |   0.927007 |   0.965108 |    0.965345 |       0.965284 |  0.101164 |
| recall    |   0.984962 |   0.992647 |   0.992481 |   0.956204 |   0.963235 |   0.955882 |   0.963235 |   0.985075 |   0.916031 |   0.940741 |   0.965108 |    0.965049 |       0.965108 |  0.101164 |
| f1-score  |   0.981273 |   0.967742 |   0.988764 |   0.959707 |   0.96679  |   0.962963 |   0.97037  |   0.977778 |   0.941176 |   0.933824 |   0.965108 |    0.965039 |       0.965039 |  0.101164 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.965108 | 1347        |    1347        |  0.101164 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              131 |                0 |                0 |                0 |                2 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              135 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |                1 |
| Labeled as 2 |                1 |                0 |              132 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |              131 |                0 |                2 |                0 |                1 |                2 |                1 |
| Labeled as 4 |                0 |                1 |                0 |                0 |              131 |                0 |                1 |                0 |                0 |                3 |
| Labeled as 5 |                0 |                1 |                0 |                0 |                0 |              130 |                1 |                0 |                0 |                4 |
| Labeled as 6 |                1 |                1 |                1 |                0 |                0 |                1 |              131 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                1 |                0 |                0 |                1 |                0 |                0 |              132 |                0 |                0 |
| Labeled as 8 |                1 |                3 |                1 |                2 |                1 |                0 |                1 |                1 |              120 |                1 |
| Labeled as 9 |                0 |                1 |                0 |                3 |                0 |                1 |                0 |                2 |                1 |              127 |

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
