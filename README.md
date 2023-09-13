# machineFailurePrediction
Binary classification (machine failure prediction) and recall optimization for unbalanced datasets. Comparing XGB, LR, L1, JT, scenarios and algorithms to check performance.

# Recall Results: 

![image](https://github.com/santtiospina/machineFailurePrediction/assets/75998236/e0afdba3-7cb6-43f6-aecc-a55d57f12324)

## Improved recall from 47.26% to 95.21% using Synthetic Minority Oversampling Technique and Extreme Gradient Boosting (XGBoost)

The 47.26% recall was obtained using Johnson Transformations to the features and L1 regularization with alpha=0.07 

The Synthetic Minority Oversampling Technique (SMOTE) was necessary because of an imbalanced (98:2) dataset -> 98% of the entries machine failure was == 0

<img width="867" alt="Captura de pantalla 2023-09-13 a la(s) 1 18 07 p m" src="https://github.com/santtiospina/machineFailurePrediction/assets/75998236/f3fcec8e-3738-4366-b8d9-afdb0dfaff72">


With feature engineering, removing multicollinearity, encoding categorial variables and oversampling the desired predicted feature the model was able to obtain:

Accuracy: 0.9985

Precision: 0.9542

Recall: 0.9521

F1 Score: 0.9531
