# Credit_Risk_Analysis
## Purpose:
The purpose of this analysis was to train and evaluate the data in order to determine credit risk on loans. We did so using machine learning programs to help us evaluate the data. 

## Results:
- RandomOverSampler Accuracy: 0.67 Average Precision: 0.99 Average Recall: 0.61
<img width="610" alt="Screen Shot 2021-06-13 at 8 16 41 PM" src="https://user-images.githubusercontent.com/75695931/121826189-76741300-cc84-11eb-8a87-4f4106a357e6.png">
- SMOTE Accuracy: 0.66 Average Precision: 0.99 Average Recall: 0.69
<img width="591" alt="Screen Shot 2021-06-13 at 8 16 54 PM" src="https://user-images.githubusercontent.com/75695931/121826190-76741300-cc84-11eb-9810-08451a99b600.png">
- ClusterCentroids Accuracy: 0.52 Average Precision: 0.99 Average Recall: 0.40
<img width="591" alt="Screen Shot 2021-06-13 at 8 17 10 PM" src="https://user-images.githubusercontent.com/75695931/121826191-76741300-cc84-11eb-9ec6-9980a051ea15.png">
- SMOTEENN Accuracy: 0.66 Average Precision: 0.99 Average Recall: 0.59
<img width="573" alt="Screen Shot 2021-06-13 at 8 17 21 PM" src="https://user-images.githubusercontent.com/75695931/121826192-76741300-cc84-11eb-9d57-2c8cc99ebb20.png">
- BalancedRandomForestClassifier Accuracy: 0.78 Average Precision: 0.99 Average Recall: 0.87
<img width="565" alt="Screen Shot 2021-06-13 at 8 17 38 PM" src="https://user-images.githubusercontent.com/75695931/121826193-770ca980-cc84-11eb-987d-d4e1187844b7.png">
- EasyEnsembleClassifier Accuracy: 0.93 Average Precision: 0.99 Average Recall: 0.94
<img width="575" alt="Screen Shot 2021-06-13 at 8 17 48 PM" src="https://user-images.githubusercontent.com/75695931/121826194-770ca980-cc84-11eb-9f0a-d93e08fa7e04.png">



## Summary:
The accuracy of the data essentially tells us if we can trust the information we are getting or not, and it would appear that we do not have very accurate data. with most results ranging from between .52-.70 we can see that our data may not be the most accurate and some loans might be mislabled as hihg or low risk. Our data is very precise at first glance by looking at the averages, but when we take a closer look in particular at the easyensembleclassifier that the model was most precise when it came to low risk loans and not so much high risk. While none of these are great options it would be best to use the precision model because it will result in more low-risk loans being granted which in the long run will be the safest option. 
