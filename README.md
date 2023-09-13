# machineFailurePrediction
Binary classification (machine failure prediction) and recall optimization for unbalanced datasets. Comparing XGB, LR, L1, JT, and more to check performance.

# First Results: 

## Improve recall from 47.26% to 95.21% using Synthetic Minority Oversampling Technique and Extreme Gradient Boosting 

The 47.26% recall was obtained using Johnson Transformations to the features and L1 regularization with alpha=0.07 

The Synthetic Minority Oversampling Technique (SMOTE) was necessary because of an imbalanced (98:2) dataset which means that in 98% of the entries the machine didn't fail, and just in 2% of the entries it did fail. 

With feature engineering, removing multicollinearity, encoding categorial variables and oversampling the desired predicted feature the model was able to obtain:
Accuracy: 0.9985
Precision: 0.9542
Recall: 0.9521
F1 Score: 0.9531

The first XGBoost approach obtained:
Accuracy: 0.9960
Precision: 0.9633
Recall: 0.7785
F1 Score: 0.8611
