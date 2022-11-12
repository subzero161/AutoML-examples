# Summary of 19_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 16
- **learning_rate**: 0.01
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

6.4 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.992308 |   0.956204 |   0.985075 |   0.955882 |   0.977444 |   0.927536 |   0.963504 |   0.963235 |   0.902985 |   0.931818 |   0.955457 |    0.955599 |       0.955654 |   0.15857 |
| recall    |   0.969925 |   0.963235 |   0.992481 |   0.948905 |   0.955882 |   0.941176 |   0.970588 |   0.977612 |   0.923664 |   0.911111 |   0.955457 |    0.955458 |       0.955457 |   0.15857 |
| f1-score  |   0.980989 |   0.959707 |   0.988764 |   0.952381 |   0.966543 |   0.934307 |   0.967033 |   0.97037  |   0.913208 |   0.921348 |   0.955457 |    0.955465 |       0.955492 |   0.15857 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.955457 | 1347        |    1347        |   0.15857 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              129 |                0 |                1 |                0 |                1 |                0 |                2 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              131 |                0 |                1 |                0 |                1 |                1 |                0 |                2 |                0 |
| Labeled as 2 |                0 |                0 |              132 |                0 |                0 |                0 |                0 |                0 |                1 |                0 |
| Labeled as 3 |                0 |                0 |                1 |              130 |                0 |                1 |                0 |                0 |                3 |                2 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              130 |                1 |                0 |                2 |                2 |                1 |
| Labeled as 5 |                0 |                1 |                0 |                0 |                1 |              128 |                2 |                0 |                0 |                4 |
| Labeled as 6 |                1 |                1 |                0 |                0 |                0 |                1 |              132 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                1 |                1 |                0 |                0 |              131 |                1 |                0 |
| Labeled as 8 |                0 |                3 |                0 |                3 |                0 |                2 |                0 |                0 |              121 |                2 |
| Labeled as 9 |                0 |                1 |                0 |                1 |                0 |                4 |                0 |                3 |                3 |              123 |

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
