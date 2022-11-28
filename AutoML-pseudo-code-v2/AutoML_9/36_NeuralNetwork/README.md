# Summary of 36_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 16
- **learning_rate**: 0.05
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

9.4 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.992366 |   0.949275 |   0.955556 |   0.948905 |   0.964029 |   0.956204 |   0.963504 |   0.929577 |   0.958678 |   0.946154 |   0.956199 |    0.956425 |       0.95638  |  0.300124 |
| recall    |   0.977444 |   0.963235 |   0.969925 |   0.948905 |   0.985294 |   0.963235 |   0.970588 |   0.985075 |   0.885496 |   0.911111 |   0.956199 |    0.956031 |       0.956199 |  0.300124 |
| f1-score  |   0.984848 |   0.956204 |   0.962687 |   0.948905 |   0.974545 |   0.959707 |   0.967033 |   0.956522 |   0.920635 |   0.928302 |   0.956199 |    0.955939 |       0.956005 |  0.300124 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.956199 | 1347        |    1347        |  0.300124 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              130 |                0 |                0 |                0 |                1 |                0 |                1 |                0 |                1 |                0 |
| Labeled as 1 |                0 |              131 |                0 |                2 |                0 |                0 |                1 |                0 |                0 |                2 |
| Labeled as 2 |                1 |                0 |              129 |                1 |                1 |                0 |                0 |                1 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                2 |              130 |                0 |                2 |                0 |                1 |                1 |                1 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              134 |                0 |                0 |                1 |                1 |                0 |
| Labeled as 5 |                0 |                0 |                1 |                0 |                1 |              131 |                2 |                0 |                0 |                1 |
| Labeled as 6 |                0 |                1 |                0 |                0 |                1 |                2 |              132 |                0 |                0 |                0 |
| Labeled as 7 |                0 |                0 |                1 |                0 |                0 |                0 |                0 |              132 |                0 |                1 |
| Labeled as 8 |                0 |                5 |                2 |                1 |                1 |                1 |                1 |                2 |              116 |                2 |
| Labeled as 9 |                0 |                1 |                0 |                3 |                0 |                1 |                0 |                5 |                2 |              123 |

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
