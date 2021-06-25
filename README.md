# Credit_Risk_Analysis

## Overview
In this analysis we are evaluating credit risk. We will need to employ different techniques to train and evaluate models with unbalanced classes. To do this we will use six different machine learning algorithms to undersample and oversample the data to reduce as much bias as possible. We will be using RandomOverSampler and SMOTE to oversample the data, ClusterCentroids to undersample the data, SMOTEENN to combine over- and undersampling, and BalancedRandomForestClassifier and EasyEnsembleClassifier to reduce bias.

## Results
To analyze our results we will look at accuracy scores, precision scores, and recall scores of each algorithm.

- RandomOverSampler-  
  accuracy score: 0.64  https://user-images.githubusercontent.com/79720084/123367817-3e9c8380-d540-11eb-837e-31bfc50a4f8d.png
  precision score: 1.0  
  recall score: 0.66  https://user-images.githubusercontent.com/79720084/123368299-2416da00-d541-11eb-8788-7ccbf4438cf8.png


- SMOTE-  
  accuracy score: 0.615  https://user-images.githubusercontent.com/79720084/123367855-5542da80-d540-11eb-9a2a-c73df898d8cf.png
  precision score: 1.0  
  recall score: 0.59  https://user-images.githubusercontent.com/79720084/123367863-57a53480-d540-11eb-8751-160090b3b333.png

- ClusterCentroids-     
  accuracy score: 0.52  https://user-images.githubusercontent.com/79720084/123367880-5ecc4280-d540-11eb-972b-91da359bc064.png
  precision score: 1.0  
  recall score: 0.43  https://user-images.githubusercontent.com/79720084/123367890-612e9c80-d540-11eb-870b-62e05e0cbe4b.png

- SMOTEENN-     
  accuracy score: 0.65  https://user-images.githubusercontent.com/79720084/123367898-64c22380-d540-11eb-8cf5-6b5d2c51c6ad.png
  precision score: 1.0  
  recall score: 0.59  https://user-images.githubusercontent.com/79720084/123367905-67247d80-d540-11eb-9e45-54f7964ce3b1.png

- BalancedRandomForestClassifier-      
  accuracy score: 0.795   https://user-images.githubusercontent.com/79720084/123367922-6db2f500-d540-11eb-8c60-3027304d576e.png
  precision score: 1.0  
  recall score: 0.9   https://user-images.githubusercontent.com/79720084/123367927-71467c00-d540-11eb-9279-cbc91d1c2021.png

- EasyEnsembleClassifier-      
  accuracy score: 0.925   https://user-images.githubusercontent.com/79720084/123367936-77d4f380-d540-11eb-989f-022772fd1df3.png
  precision score: 1.0  
  recall score: 0.94   https://user-images.githubusercontent.com/79720084/123367942-7acfe400-d540-11eb-95f3-3704b4d460a9.png


## Summary




