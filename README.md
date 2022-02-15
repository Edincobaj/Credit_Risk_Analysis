# Credit_Risk_Analysis

## Overview
In this challenge we've been tasked with using machine learning to solve a real-world challenge, credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. We'll be comparing balanced accuracy scores and the precision and recall scores of all six machine learning models.

## Results

#### -Random Oversampling
* Balanced Accuracy Score: 0.62
* Precision Score: high_risk: 0.01/low_risk: 1.00
* Recall Score: high_risk: 0.63/low_risk: 0.60
![random_oversampling](https://user-images.githubusercontent.com/41974323/154157603-979d97a0-4876-4339-bd3c-405d69eedcb7.PNG)

#### -SMOTE Oversampling
* Balanced Accuracy Score: 0.66
* Precision Score: high_risk: 0.01/low_risk: 1.00
* Recall Score: high_risk: 0.63/low_risk: 0.69
![SMOTE_oversampling](https://user-images.githubusercontent.com/41974323/154157772-ac2ea397-5b7a-41e4-8a8c-2d4e53f3bbf9.PNG)

#### -ClusterCentroids
* Balanced Accuracy Score: 0.54
* Precision Score: high_risk: 0.01/low_risk: 1.00
* Recall Score: high_risk: 0.69/low_risk: 0.40
![ClusterCentroids](https://user-images.githubusercontent.com/41974323/154158050-a66fd654-5fdb-4782-bc9a-574753b2cb53.PNG)

#### -SMOTEENN Combination Sampling
* Balanced Accuracy Score: 0.64
* Precision Score: high_risk: 0.01/low_risk: 1.00
* Recall Score: high_risk: 0.72/low_risk: 0.57
![SMOTEENN_Combination_Sampling](https://user-images.githubusercontent.com/41974323/154158307-c2674a7b-cbdd-4a45-a20d-08178cf55e0a.PNG)

#### -Balanced Random Forest Classifier
* Balanced Accuracy Score: 0.79
* Precision Score: high_risk: 0.03/low_risk: 1.00
* Recall Score: high_risk: 0.70/low_risk: 0.87
![Balanced_Random_Forest_Classifier](https://user-images.githubusercontent.com/41974323/154158629-7ee50bff-f228-472e-8152-d147c4b2f54d.PNG)

#### -AdaBoost Classifier
* Balanced Accuracy Score: 0.93
* Precision Score: high_risk: 0.09/low_risk: 1.00
* Recall Score: high_risk: 0.92/low_risk: 0.94
![Adaboost_classifier](https://user-images.githubusercontent.com/41974323/154158922-11180819-4dcb-49fd-862d-0daa17d12cd1.PNG)

## Summary
According to our results our analysis shows that the Adaboost classifier model shows the best scores across balanced accuracy, precision and recall when compared to other models. In my opinion the recommended model to use is the Adaboost classifier model because the model shows the best ability to limit the number of high-risk loans going through without getting flagged. 







