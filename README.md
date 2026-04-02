# Analitica_Proyecto

## 📊 Comparación de Modelos Santiago

| Ranking | Modelo              | Recall (Sensibilidad) | Precisión | F1-Score | Accuracy |
|--------:|---------------------|----------------------:|----------:|---------:|---------:|
| 1 | CatBoost            | 0.3949 | 0.7642 | 0.5207 | 0.9404 |
| 2 | XGBoost             | 0.3940 | 0.7656 | 0.5203 | 0.9404 |
| 3 | RandomForest        | 0.3901 | 0.7684 | 0.5175 | 0.9403 |
| 4 | RedNeuronal         | 0.3848 | 0.7714 | 0.5135 | 0.9402 |
| 5 | RegLineal_Stepwise  | 0.3636 | 0.7621 | 0.4923 | 0.9385 |
| 6 | ElasticNet          | 0.3627 | 0.7630 | 0.4917 | 0.9385 |

## 📊 Comparación de Modelos Camilo

| Ranking | Modelo              | Recall (Sensibilidad) | Precisión | F1-Score | Accuracy |
|--------:|---------------------|----------------------:|----------:|---------:|---------:|
| 1 | LGBM             |  |  |  |  |
| 2 | RandomForest        |  |  |  |  |
| 5 | SVM  |  |  |  |  |

## 📊 Comparación de Modelos Edgar

| Ranking | Modelo              | Recall (Sensibilidad) | Precisión | F1-Score | Accuracy |
|--------:|---------------------|----------------------:|----------:|---------:|---------:|
| 1 | xgboost             |  |  |  |  |
| 2 | RandomForest        |  |  |  |  |
| 5 | SVM  |  |  |  |  |

## 📊 Comparación de Modelos Emanuel

| # | Modelo        | Precision (Clase 1) | Recall (Clase 1) | F1-Score (Clase 1) |
|---|---------------|---------------------:|-----------------:|-------------------:|
| 0 | LR_SMOTE      | 0.334147 | 0.772500 | 0.466506 |
| 1 | RandomForest  | 0.339956 | 0.780273 | 0.473579 |
| 2 | XGBoost       | 0.389208 | 0.742155 | 0.510627 |

## 📊 Comparación de Modelos Juan D


| #  | Modelo                           | MAE_valid | RMSE_valid | MAE_test | RMSE_test |
|----|----------------------------------|----------:|-----------:|---------:|----------:|
| 0  | XGBoost                          | 0.762 | 0.986 | 0.762 | 0.985 |
| 1  | Gradient Boosting profundo       | 0.762 | 0.986 | 0.762 | 0.985 |
| 2  | Random Forest (depth=20, 5-5)    | 0.765 | 0.988 | 0.765 | 0.988 |
| 3  | Gradient Boosting                | 0.765 | 0.989 | 0.765 | 0.989 |
| 4  | SVR RBF                          | 0.766 | 0.995 | 0.766 | 0.995 |
| 5  | Random Forest (depth=60, 5-5)    | 0.771 | 0.995 | 0.771 | 0.994 |
| 6  | SVR polinómico                   | 0.779 | 1.011 | 0.778 | 1.010 |
| 7  | Random Forest (depth=40, 2-2)    | 0.789 | 1.017 | 0.789 | 1.017 |
| 8  | SVR lineal                       | 0.798 | 1.031 | 0.799 | 1.031 |
| 9  | Regresión lineal                 | 0.798 | 1.031 | 0.799 | 1.030 |
| 10 | Ingenuo                          | 0.959 | 1.305 | 0.959 | 1.305 |

## 📊 Comparación de Modelos Johnny

| # | Modelo          | Accuracy | Precision (bajo peso) | Recall (bajo peso) | F1 (bajo peso) | ROC AUC | PR AUC |
|---|-----------------|---------:|----------------------:|-------------------:|----------------:|--------:|-------:|
| 0 | SVM (LinearSVC) | 0.8829 | 0.3777 | 0.7494 | 0.5023 | 0.8868 | 0.6103 |
| 2 | XGBoost         | 0.8855 | 0.3818 | 0.7299 | 0.5014 | 0.8866 | 0.6139 |
| 1 | Random Forest   | 0.9378 | 0.6342 | 0.4981 | 0.5580 | 0.8785 | 0.5861 |


## Métricas de modelos unificado

| Modelo | Accuracy Test | Accuracy Train | Accuracy Val | F1 Test | F1 Train | F1 Val | PR AUC Test | PR AUC Train | PR AUC Val | Precision Test | Precision Train | Precision Val | Recall Test | Recall Train | Recall Val | ROC AUC Test | ROC AUC Train | ROC AUC Val |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| BaggingClassifier | 0.8723 | 0.8755 | 0.8707 | 0.4876 | 0.5020 | 0.4821 | 0.6219 | 0.6526 | 0.6104 | 0.3566 | 0.3666 | 0.3524 | 0.7708 | 0.7957 | 0.7629 | 0.8905 | 0.9195 | 0.8876 |
| CalibratedLinearSVC | 0.9415 | 0.9415 | 0.9401 | 0.5041 | 0.5122 | 0.4941 | 0.6063 | 0.6140 | 0.5977 | 0.7598 | 0.7472 | 0.7407 | 0.3772 | 0.3896 | 0.3707 | 0.8847 | 0.8897 | 0.8855 |
| LogisticRegression | 0.8863 | 0.8870 | 0.8842 | 0.5074 | 0.5104 | 0.5014 | 0.6090 | 0.6181 | 0.6013 | 0.3853 | 0.3876 | 0.3796 | 0.7429 | 0.7473 | 0.7384 | 0.8844 | 0.8899 | 0.8851 |
| RandomForestClassifier | 0.8770 | 0.8804 | 0.8755 | 0.4954 | 0.5092 | 0.4895 | 0.6108 | 0.6406 | 0.5957 | 0.3661 | 0.3763 | 0.3618 | 0.7662 | 0.7870 | 0.7566 | 0.8931 | 0.9198 | 0.8895 |
| XGBClassifier | 0.8763 | 0.8887 | 0.8743 | 0.4891 | 0.5433 | 0.4844 | 0.6136 | 0.7300 | 0.6024 | 0.3626 | 0.4016 | 0.3581 | 0.7510 | 0.8393 | 0.7485 | 0.8859 | 0.9423 | 0.8848 |
