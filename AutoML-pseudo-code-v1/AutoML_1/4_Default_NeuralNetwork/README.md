# Summary of 4_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
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

4.1 seconds

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.992248 |   0.93617  |   0.942446 |   0.962406 |   0.942446 |   0.963235 |   0.977941 |   0.956204 |   0.937008 |   0.953846 |   0.956199 |    0.956395 |       0.956425 |  0.244656 |
| recall    |   0.962406 |   0.970588 |   0.984962 |   0.934307 |   0.963235 |   0.963235 |   0.977941 |   0.977612 |   0.908397 |   0.918519 |   0.956199 |    0.95612  |       0.956199 |  0.244656 |
| f1-score  |   0.977099 |   0.953069 |   0.963235 |   0.948148 |   0.952727 |   0.963235 |   0.977941 |   0.96679  |   0.922481 |   0.935849 |   0.956199 |    0.956057 |       0.956112 |  0.244656 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.956199 | 1347        |    1347        |  0.244656 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              128 |                0 |                1 |                0 |                2 |                0 |                1 |                0 |                1 |                0 |
| Labeled as 1 |                0 |              132 |                2 |                0 |                1 |                0 |                1 |                0 |                0 |                0 |
| Labeled as 2 |                0 |                0 |              131 |                1 |                0 |                0 |                0 |                0 |                1 |                0 |
| Labeled as 3 |                0 |                0 |                2 |              128 |                0 |                2 |                0 |                0 |                2 |                3 |
| Labeled as 4 |                0 |                1 |                0 |                0 |              131 |                0 |                0 |                2 |                1 |                1 |
| Labeled as 5 |                0 |                0 |                0 |                1 |                0 |              131 |                1 |                1 |                1 |                1 |
| Labeled as 6 |                0 |                2 |                0 |                0 |                1 |                0 |              133 |                0 |                0 |                0 |
| Labeled as 7 |                0 |                0 |                1 |                1 |                1 |                0 |                0 |              131 |                0 |                0 |
| Labeled as 8 |                0 |                5 |                2 |                0 |                1 |                2 |                0 |                1 |              119 |                1 |
| Labeled as 9 |                1 |                1 |                0 |                2 |                2 |                1 |                0 |                2 |                2 |              124 |

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
