# Summary of 15_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 30
- **max_depth**: 7
- **eval_metric_name**: logloss
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

16.3 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.977444 |   0.898551 |   0.976562 |   0.920635 |   0.934783 |   0.941606 |   0.992424 |   0.883562 |   0.860465 |   0.842857 |   0.922049 |    0.922889 |       0.922996 |  0.447175 |
| recall    |   0.977444 |   0.911765 |   0.93985  |   0.846715 |   0.948529 |   0.948529 |   0.963235 |   0.962687 |   0.847328 |   0.874074 |   0.922049 |    0.922016 |       0.922049 |  0.447175 |
| f1-score  |   0.977444 |   0.905109 |   0.957854 |   0.882129 |   0.941606 |   0.945055 |   0.977612 |   0.921429 |   0.853846 |   0.858182 |   0.922049 |    0.922027 |       0.922095 |  0.447175 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.922049 | 1347        |    1347        |  0.447175 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                2 |                0 |                0 |                0 |                1 |                0 |
| Labeled as 1 |                0 |              124 |                0 |                1 |                1 |                1 |                0 |                0 |                2 |                7 |
| Labeled as 2 |                1 |                1 |              125 |                4 |                0 |                0 |                0 |                1 |                0 |                1 |
| Labeled as 3 |                0 |                1 |                1 |              116 |                0 |                5 |                0 |                2 |                9 |                3 |
| Labeled as 4 |                0 |                2 |                0 |                0 |              129 |                1 |                0 |                2 |                1 |                1 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                1 |              129 |                1 |                0 |                0 |                5 |
| Labeled as 6 |                1 |                0 |                0 |                0 |                3 |                0 |              131 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                1 |                0 |                1 |                1 |                0 |                0 |              129 |                1 |                1 |
| Labeled as 8 |                1 |                7 |                2 |                1 |                1 |                1 |                0 |                3 |              111 |                4 |
| Labeled as 9 |                0 |                2 |                0 |                3 |                0 |                0 |                0 |                9 |                3 |              118 |

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
