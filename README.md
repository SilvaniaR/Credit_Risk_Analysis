# Credit_Risk_Analysis
Supervised ML

## Overview of the analysis: 
The purpose of this analysis was to find a model that can best predict credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we employ different techniques to train and evaluate models with unbalanced classes. Throughout the analysis we employed 6 different models; RandomOverSampler, SMOTE,ClusterCentroids, SMOTEENN,BalancedRandomForestClassifier, and EasyEnsembleClassifier to find the best one that can predict credit risk.

## Results: 
* RandomOverSampler

<img width="1170" alt="naive_randomoversampling" src="https://user-images.githubusercontent.com/93267002/164953604-e362fe6c-c02e-4bad-bd13-8a8d87ea74bc.png">


* SMOTE

<img width="1173" alt="SMOTE" src="https://user-images.githubusercontent.com/93267002/164953610-35383634-108d-419a-b5c1-847fd8393c24.png">

* ClusterCentroids

<img width="1144" alt="Clustercentroids" src="https://user-images.githubusercontent.com/93267002/164953612-02f8d116-7fb9-49e9-8c41-787cc9d3ad72.png">


* SMOTEENN

<img width="1140" alt="SMOTEENN" src="https://user-images.githubusercontent.com/93267002/164953619-c52fce45-e09d-41be-a319-8cb8265c7d90.png">



* BalancedRandomForestClassifier

<img width="1135" alt="Balancedrandomforestclassifier" src="https://user-images.githubusercontent.com/93267002/164953622-0de3a88b-e3ad-4ef6-8e32-32da7e4eb5a7.png">



* EasyEnsembleClassifier


<img width="1172" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/93267002/164953627-a1a24a99-ca89-4770-9ca3-a8b4eb91caff.png">



## Summary: 
After carefully looking at the rrsults for each model, I would use the EasyEnsembleClassifier or the random forest classifier. The Easy Ensemnle Classifier has the highest accuracy score for its model. I thinks if will give us the better prediction out all models above becuase easy ensemble uses mutiple algorithms which result into multiple predictions to gives us the best prediction as the final outcome. Both of these model use similar concept in combining smaller model/decision trees to come up with a final outcome.
