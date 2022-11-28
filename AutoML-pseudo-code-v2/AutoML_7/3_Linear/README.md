# Summary of 3_Linear

[<< Go back](../README.md)


## Logistic Regression (Linear)
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

3.0 seconds

### Metric details
|           |   0.0 |     0.01 |   0.44 |   0.49 |   0.51 |   1.0 |   5.0 |   14.0 |   16.0 |   19.0 |   639.0 |    641.0 |   719.0 |   736.0 |   1439.0 |   1455.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|------:|---------:|-------:|-------:|-------:|------:|------:|-------:|-------:|-------:|--------:|---------:|--------:|--------:|---------:|---------:|-----------:|------------:|---------------:|----------:|
| precision |     0 | 0.125    |      0 |      0 |      0 |     0 |     0 |      0 |      1 |      0 |       1 | 0.5      |       0 |       1 |        0 | 0.5      |      0.375 |    0.257812 |       0.257812 |   2.00885 |
| recall    |     0 | 1        |      0 |      0 |      0 |     0 |     0 |      0 |      1 |      0 |       1 | 1        |       0 |       1 |        0 | 1        |      0.375 |    0.375    |       0.375    |   2.00885 |
| f1-score  |     0 | 0.222222 |      0 |      0 |      0 |     0 |     0 |      0 |      1 |      0 |       1 | 0.666667 |       0 |       1 |        0 | 0.666667 |      0.375 |    0.284722 |       0.284722 |   2.00885 |
| support   |     5 | 5        |      5 |      5 |      5 |     5 |     5 |      5 |      5 |      5 |       5 | 5        |       5 |       5 |        5 | 5        |      0.375 |   80        |      80        |   2.00885 |


## Confusion matrix
|                   |   Predicted as 0.0 |   Predicted as 0.01 |   Predicted as 0.44 |   Predicted as 0.49 |   Predicted as 0.51 |   Predicted as 1.0 |   Predicted as 5.0 |   Predicted as 14.0 |   Predicted as 16.0 |   Predicted as 19.0 |   Predicted as 639.0 |   Predicted as 641.0 |   Predicted as 719.0 |   Predicted as 736.0 |   Predicted as 1439.0 |   Predicted as 1455.0 |
|:------------------|-------------------:|--------------------:|--------------------:|--------------------:|--------------------:|-------------------:|-------------------:|--------------------:|--------------------:|--------------------:|---------------------:|---------------------:|---------------------:|---------------------:|----------------------:|----------------------:|
| Labeled as 0.0    |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.01   |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.44   |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.49   |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 0.51   |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 1.0    |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 5.0    |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 14.0   |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  5 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 16.0   |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   5 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 19.0   |                  0 |                   5 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 639.0  |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    5 |                    0 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 641.0  |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    5 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 719.0  |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    5 |                    0 |                    0 |                     0 |                     0 |
| Labeled as 736.0  |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    5 |                     0 |                     0 |
| Labeled as 1439.0 |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     5 |
| Labeled as 1455.0 |                  0 |                   0 |                   0 |                   0 |                   0 |                  0 |                  0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     5 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients

### Coefficients learner #1
|           |       0.0 |      0.01 |       0.44 |       0.49 |       0.51 |        1.0 |       5.0 |      14.0 |      16.0 |       19.0 |    639.0 |    641.0 |    719.0 |   736.0 |   1439.0 |   1455.0 |
|:----------|----------:|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|---------:|---------:|---------:|--------:|---------:|---------:|
| intercept |  0.382868 | -0.097713 | -0.0976642 | -0.0976651 | -0.0976322 | -0.0951958 |  0.335445 |  0.540521 |  0.81812  |  0.0669911 | 0.999076 | 0.856634 | 0.865288 | 0.31566 | -1.44736 | -3.24737 |
| total     | -1.0952   | -1.93315  | -1.93307   | -1.93307   | -1.93302   | -1.929     | -1.18345  | -0.787248 | -0.141147 | -1.65753   | 0.591199 | 1.63114  | 1.61053  | 2.41432 |  3.67671 |  4.60199 |


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



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence 0.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.0.png)
### Dependence 0.01 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.01.png)
### Dependence 0.44 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.44.png)
### Dependence 0.49 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.49.png)
### Dependence 0.51 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.51.png)
### Dependence 1.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_1.0.png)
### Dependence 14.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_14.0.png)
### Dependence 1439.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_1439.0.png)
### Dependence 1455.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_1455.0.png)
### Dependence 16.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_16.0.png)
### Dependence 19.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_19.0.png)
### Dependence 5.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_5.0.png)
### Dependence 639.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_639.0.png)
### Dependence 641.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_641.0.png)
### Dependence 719.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_719.0.png)
### Dependence 736.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_736.0.png)

## SHAP Decision plots

### Worst decisions for selected sample 1 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_0_worst_decisions.png)
### Worst decisions for selected sample 2 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_1_worst_decisions.png)
### Worst decisions for selected sample 3 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_2_worst_decisions.png)
### Worst decisions for selected sample 4 (Fold 1)
![SHAP worst decisions from Fold 1](learner_fold_0_sample_3_worst_decisions.png)
### Best decisions for selected sample 1 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_0_best_decisions.png)
### Best decisions for selected sample 2 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_1_best_decisions.png)
### Best decisions for selected sample 3 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_2_best_decisions.png)
### Best decisions for selected sample 4 (Fold 1)
![SHAP best decisions from Fold 1](learner_fold_0_sample_3_best_decisions.png)

[<< Go back](../README.md)
