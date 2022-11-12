# Summary of 28_NeuralNetwork_SelectedFeatures

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
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

5.6 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.977273 |   0.955882 |   0.977778 |   0.941606 |   0.956835 |   0.97037  |   0.956204 |   0.977273 |   0.883721 |   0.911111 |   0.951002 |    0.950805 |       0.950919 |   0.18616 |
| recall    |   0.969925 |   0.955882 |   0.992481 |   0.941606 |   0.977941 |   0.963235 |   0.963235 |   0.962687 |   0.870229 |   0.911111 |   0.951002 |    0.950833 |       0.951002 |   0.18616 |
| f1-score  |   0.973585 |   0.955882 |   0.985075 |   0.941606 |   0.967273 |   0.96679  |   0.959707 |   0.969925 |   0.876923 |   0.911111 |   0.951002 |    0.950788 |       0.950929 |   0.18616 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.951002 | 1347        |    1347        |   0.18616 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              129 |                0 |                1 |                0 |                2 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              130 |                0 |                1 |                1 |                0 |                2 |                0 |                2 |                0 |
| Labeled as 2 |                1 |                0 |              132 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                1 |              129 |                0 |                2 |                0 |                0 |                3 |                2 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              133 |                0 |                0 |                0 |                2 |                1 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              131 |                0 |                1 |                2 |                2 |
| Labeled as 6 |                2 |                2 |                0 |                0 |                1 |                0 |              131 |                0 |                0 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                1 |                0 |                2 |              129 |                1 |                1 |
| Labeled as 8 |                0 |                4 |                1 |                3 |                0 |                1 |                1 |                1 |              114 |                6 |
| Labeled as 9 |                0 |                0 |                0 |                4 |                1 |                1 |                0 |                1 |                5 |              123 |

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
