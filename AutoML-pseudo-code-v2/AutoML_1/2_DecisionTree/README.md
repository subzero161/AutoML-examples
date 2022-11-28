# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **num_class**: 20
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

10.7 seconds

### Metric details
|           |       0.0 |   0.18 |   0.27 |   0.45 |   32.0 |   42.0 |   59.0 |   67.0 |   75.0 |   80.0 |   115.0 |   137.0 |   337.0 |   643.0 |   2151.0 |   2303.0 |   2515.0 |   6357.0 |   7693.0 |   11899.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|-------:|-------:|-------:|-------:|-------:|-------:|-------:|-------:|-------:|--------:|--------:|--------:|--------:|---------:|---------:|---------:|---------:|---------:|----------:|-----------:|------------:|---------------:|----------:|
| precision | 0.0588235 |      0 |      0 |      0 |      1 |      0 |      0 |      0 |      0 |      0 |       0 |       0 |       0 |       1 |        0 |        0 |        1 |        0 |        0 |         0 |        0.2 |    0.152941 |       0.152941 |   2.40824 |
| recall    | 1         |      0 |      0 |      0 |      1 |      0 |      0 |      0 |      0 |      0 |       0 |       0 |       0 |       1 |        0 |        0 |        1 |        0 |        0 |         0 |        0.2 |    0.2      |       0.2      |   2.40824 |
| f1-score  | 0.111111  |      0 |      0 |      0 |      1 |      0 |      0 |      0 |      0 |      0 |       0 |       0 |       0 |       1 |        0 |        0 |        1 |        0 |        0 |         0 |        0.2 |    0.155556 |       0.155556 |   2.40824 |
| support   | 5         |      5 |      5 |      5 |      5 |      5 |      5 |      5 |      5 |      5 |       5 |       5 |       5 |       5 |        5 |        5 |        5 |        5 |        5 |         5 |        0.2 |  100        |     100        |   2.40824 |


## Confusion matrix
|                    |   Predicted as 0.0 |   Predicted as 0.18 |   Predicted as 0.27 |   Predicted as 0.45 |   Predicted as 32.0 |   Predicted as 42.0 |   Predicted as 59.0 |   Predicted as 67.0 |   Predicted as 75.0 |   Predicted as 80.0 |   Predicted as 115.0 |   Predicted as 137.0 |   Predicted as 337.0 |   Predicted as 643.0 |   Predicted as 2151.0 |   Predicted as 2303.0 |   Predicted as 2515.0 |   Predicted as 6357.0 |   Predicted as 7693.0 |   Predicted as 11899.0 |
|:-------------------|-------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|--------------------:|---------------------:|---------------------:|---------------------:|---------------------:|----------------------:|----------------------:|----------------------:|----------------------:|----------------------:|-----------------------:|
| Labeled as 0.0     |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 0.18    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 0.27    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 0.45    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 32.0    |                  0 |                   0 |                   0 |                   0 |                   5 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 42.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 59.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 67.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 75.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 80.0    |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 115.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 137.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 337.0   |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 643.0   |                  0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    5 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 2151.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 2303.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 2515.0  |                  0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     5 |                     0 |                     0 |                      0 |
| Labeled as 6357.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 7693.0  |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |
| Labeled as 11899.0 |                  5 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                   0 |                    0 |                    0 |                    0 |                    0 |                     0 |                     0 |                     0 |                     0 |                     0 |                      0 |

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



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence 0.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.0.png)
### Dependence 0.18 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.18.png)
### Dependence 0.27 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.27.png)
### Dependence 0.45 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_0.45.png)
### Dependence 115.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_115.0.png)
### Dependence 11899.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_11899.0.png)
### Dependence 137.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_137.0.png)
### Dependence 2151.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_2151.0.png)
### Dependence 2303.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_2303.0.png)
### Dependence 2515.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_2515.0.png)
### Dependence 32.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_32.0.png)
### Dependence 337.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_337.0.png)
### Dependence 42.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_42.0.png)
### Dependence 59.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_59.0.png)
### Dependence 6357.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_6357.0.png)
### Dependence 643.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_643.0.png)
### Dependence 67.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_67.0.png)
### Dependence 75.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_75.0.png)
### Dependence 7693.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_7693.0.png)
### Dependence 80.0 (Fold 1)
![SHAP Dependence from fold 1](learner_fold_0_shap_dependence_class_80.0.png)

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
