# Credit_Risk_Analysis

## Overview  
The objective of this analysis was to use machine learning models   
to predict credit risk. The methods used were oversampling,  
undersampling, comparing two machine learning models, and a  
SMOTEENN algorithm.  

Using the above methods we were able to approximate credit risk.  

## Results  
***Naive Random Oversampling***    
Balanced accuracy score - 63%    
High risk precision ~ 1%  
Low risk category had so few datapoints its precision is close to 100%  
![image](https://user-images.githubusercontent.com/91306342/156549611-d5dd97d1-e12f-44aa-923d-266a33c9864a.png)  

***SMOTE Model***  
Balanced accuracy score - 66%    
High risk precision ~ 1%  
Low risk category had so few datapoints its precision is close to 100%  
![image](https://user-images.githubusercontent.com/91306342/156549530-5333575c-8355-4559-bd0f-88c4e4358703.png)  

***Cluster Centroids Model***  
Balanced accuracy score - 66%    
High risk precision ~ 1%  
Low risk category had a high amount of false positives so the sensitivity was low (40%)  
![image](https://user-images.githubusercontent.com/91306342/156550547-6c94417e-5fed-4a17-bc93-c666f361510c.png)  

***SMOTEENN Model***  
Balancad accuracy score - 51%    
High risk precision ~ 1%  
Low risk category had a high amount of false positives so the sensitivity was 57%  
![image](https://user-images.githubusercontent.com/91306342/156557119-a37866e6-7fb2-471a-b90c-f1392114b121.png)  

***BRFC Model***  
Balancad accuracy score - 79%    
High risk precision ~ 4%  
Low risk category had a sensitivity of 91% with 100% precision  
![image](https://user-images.githubusercontent.com/91306342/156559139-fd43f393-e4ac-40cf-b4be-a1fae910bd7c.png)  

***Easy Ensemble AdaBoost Classifier***  
Balancad accuracy score - 93%    
High risk precision ~ 7%  
Low risk category had a sensitivity of 94% with 100% precision  
![image](https://user-images.githubusercontent.com/91306342/156559309-fa8020fe-6e2a-47bd-be9f-a2d3508818a7.png)

## Summary
Of all of the models the Easy Ensemble Classifier almost detected all of  
the high risk credit cases. The precision accuracy was low with all of the  
models used. Considering all methods, I would recommend the ensemble method  
of the ones tested.  
