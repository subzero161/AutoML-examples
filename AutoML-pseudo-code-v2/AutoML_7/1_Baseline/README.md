# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 16
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

0.6 seconds

### Metric details
|           |      0.0 |   0.01 |   0.44 |   0.49 |   0.51 |   1.0 |   5.0 |   14.0 |   16.0 |   19.0 |   639.0 |   641.0 |   719.0 |   736.0 |   1439.0 |   1455.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------:|-------:|-------:|-------:|-------:|------:|------:|-------:|-------:|-------:|--------:|--------:|--------:|--------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision | 0.0625   |      0 |      0 |      0 |      0 |     0 |     0 |      0 |      0 |      0 |       0 |       0 |       0 |       0 |        0 |        0 |     0.0625 |  0.00390625 |     0.00390625 |   2.77259 |
| recall    | 1        |      0 |      0 |      0 |      0 |     0 |     0 |      0 |      0 |      0 |       0 |       0 |       0 |       0 |        0 |        0 |     0.0625 |  0.0625     |     0.0625     |   2.77259 |
| f1-score  | 0.117647 |      0 |      0 |      0 |      0 |     0 |     0 |      0 |      0 |      0 |       0 |       0 |       0 |       0 |        0 |        0 |     0.0625 |  0.00735294 |     0.00735294 |   2.77259 |
| support   | 5        |      5 |      5 |      5 |      5 |     5 |     5 |      5 |      5 |      5 |       5 |       5 |       5 |       5 |        5 |        5 |     0.0625 | 80          |    80          |   2.77259 |


## Confusion matrix
|                   |   Predicted as 0.0 |   Predicted as 0.01 |   Predicted as 0.44 |   Predicted as 0.49 |   Predicted as 0.51 |   Predicted as 1.0 |   Predicted as 5.0 |   Predicted as 14.0 |   Predicted as 16.0 |   Predicted as 19.0 |   Predicted as 639.0 |   Predicted as 641.0 |   Predicted as 719.0 |   Predicted as 736.0 |   Predicted as 1439.0 |   Predicted as 1455.0 |
|:------------------|-------------------:|--------------------:|--------------------:|--------------------:|--------------------:|-------------------:|-------------------:|--------------------:|--------------------:|--------------------:|---------------------:|---------------------:|---------------------:|---------------------:|----------------------:|----------------------:|
| Labeled as 0.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.01   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.44   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.49   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.51   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 1.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 5.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 14.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 16.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 19.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 639.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 641.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 719.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 736.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 1439.0 |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 1455.0 |                  5 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
