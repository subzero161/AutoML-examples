# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                             |   Weight |
|:----------------------------------|---------:|
| 11_LightGBM                       |        1 |
| 11_LightGBM_GoldenFeatures        |        1 |
| 32_LightGBM                       |        1 |
| 35_NeuralNetwork_SelectedFeatures |        1 |

### Metric details
|           |          0 |          1 |          2 |          3 |          4 |          5 |          6 |          7 |          8 |          9 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|------------:|---------------:|----------:|
| precision |   0.984962 |   0.971223 |   1        |   0.985294 |   0.977941 |   0.970803 |   0.985075 |   0.963768 |   0.96875  |   0.947761 |   0.975501 |    0.975558 |       0.975553 | 0.0732018 |
| recall    |   0.984962 |   0.992647 |   0.992481 |   0.978102 |   0.977941 |   0.977941 |   0.970588 |   0.992537 |   0.946565 |   0.940741 |   0.975501 |    0.975451 |       0.975501 | 0.0732018 |
| f1-score  |   0.984962 |   0.981818 |   0.996226 |   0.981685 |   0.977941 |   0.974359 |   0.977778 |   0.977941 |   0.957529 |   0.944238 |   0.975501 |    0.975448 |       0.975471 | 0.0732018 |
| support   | 133        | 136        | 133        | 137        | 136        | 136        | 136        | 134        | 131        | 135        |   0.975501 | 1347        |    1347        | 0.0732018 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |   Predicted as 4 |   Predicted as 5 |   Predicted as 6 |   Predicted as 7 |   Predicted as 8 |   Predicted as 9 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |              131 |                0 |                0 |                0 |                2 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 1 |                0 |              135 |                0 |                0 |                0 |                0 |                0 |                0 |                1 |                0 |
| Labeled as 2 |                1 |                0 |              132 |                0 |                0 |                0 |                0 |                0 |                0 |                0 |
| Labeled as 3 |                0 |                0 |                0 |              134 |                0 |                1 |                0 |                2 |                0 |                0 |
| Labeled as 4 |                0 |                0 |                0 |                0 |              133 |                0 |                0 |                0 |                0 |                3 |
| Labeled as 5 |                0 |                0 |                0 |                0 |                0 |              133 |                1 |                0 |                0 |                2 |
| Labeled as 6 |                0 |                2 |                0 |                0 |                0 |                1 |              132 |                0 |                1 |                0 |
| Labeled as 7 |                0 |                0 |                0 |                0 |                1 |                0 |                0 |              133 |                0 |                0 |
| Labeled as 8 |                0 |                2 |                0 |                1 |                0 |                1 |                1 |                0 |              124 |                2 |
| Labeled as 9 |                1 |                0 |                0 |                1 |                0 |                1 |                0 |                3 |                2 |              127 |

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
