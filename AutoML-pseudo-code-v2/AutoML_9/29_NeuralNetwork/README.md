# Summary of 29_NeuralNetwork

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

8.2 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.992424 |   0.930556 |   0.984962 |   0.955882 |   0.977444 |   0.97037  |   0.963768 |   0.948905 |   0.921875 |   0.938931 |   0.958426 |    0.958512 |       0.95854  |  0.164307 |
| recall    |   0.984962 |   0.985294 |   0.984962 |   0.948905 |   0.955882 |   0.963235 |   0.977941 |   0.970149 |   0.900763 |   0.911111 |   0.958426 |    0.958321 |       0.958426 |  0.164307 |
| f1-score  |   0.988679 |   0.957143 |   0.984962 |   0.952381 |   0.966543 |   0.96679  |   0.970803 |   0.95941  |   0.911197 |   0.924812 |   0.958426 |    0.958272 |       0.958338 |  0.164307 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.958426 | 1347        |    1347        |  0.164307 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              131 |                0 |                0 |                0 |                0 |                0 |                2 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              134 |                0 |                0 |                0 |                1 |                0 |                0 |                1 |                0 |
| Labeled as 2 |                0 |                1 |              131 |                1 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |              130 |                0 |                0 |                1 |                1 |                3 |                2 |
| Labeled as 4 |                0 |                1 |                0 |                0 |              130 |                0 |                0 |                3 |                0 |                2 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                1 |              131 |                1 |                0 |                1 |                2 |
| Labeled as 6 |                1 |                2 |                0 |                0 |                0 |                0 |              133 |                0 |                0 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                1 |                2 |                0 |                0 |              130 |                1 |                0 |
| Labeled as 8 |                0 |                6 |                2 |                0 |                0 |                1 |                1 |                1 |              118 |                2 |
| Labeled as 9 |                0 |                0 |                0 |                4 |                0 |                2 |                0 |                2 |                4 |              123 |

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
