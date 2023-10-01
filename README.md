# machineFailurePrediction
Binary Classification (Machine Failure Prediction) and Recall Optimization in unbalanced datasets. 

Comparing scenarios and algorithms to check performance.

_XGBoost, L1 Regularization, Johnson Transformation, QQplots, Statistical Distributions_

# Comparing RECALL results of various models: 

![image](https://github.com/santtiospina/machineFailurePrediction/assets/75998236/e0afdba3-7cb6-43f6-aecc-a55d57f12324)

## Improved recall from 47.26% to 95.21% using Synthetic Minority Oversampling Technique and Extreme Gradient Boosting (XGBoost)

The low 47.26% recall was obtained using Johnson Transformations to the features and L1 regularization with alpha=0.07 

Recall improvement was needed. 

The Synthetic Minority Oversampling Technique (SMOTE) was necessary because of an imbalanced (98:2) dataset:

<img width="867" alt="Captura de pantalla 2023-09-13 a la(s) 1 18 07 p m" src="https://github.com/santtiospina/machineFailurePrediction/assets/75998236/f3fcec8e-3738-4366-b8d9-afdb0dfaff72">

With feature engineering, removing multicollinearity, and encoding categorial variables, the model using Synthetic Minority Oversampling Technique and Extreme Gradient Boosting (XGBoost) was able to improve recall in an imbalanced datasets obtaining:

Accuracy: 0.9985

Precision: 0.9542

Recall: 0.9521

F1 Score: 0.9531

![image](https://github.com/santtiospina/machineFailurePrediction/assets/75998236/76bd90ce-92c5-4606-804d-97ae68c381b7)

formulas taken from: https://www.tutorialexample.com/an-introduction-to-accuracy-precision-recall-f1-score-in-machine-learning-machine-learning-tutorial/



