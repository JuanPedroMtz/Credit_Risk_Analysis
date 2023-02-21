# Credit_Risk_Analysis

## Overview and analysis
We are going to help a loan company to predict the credit risk of each of the applicants with machine learning. We will help the company identificate, with machine learning, the good candidates for loans which will lead to avoid debts. We will use several machine learning models, to have different options and visualize with the actual data, which one is the best for this prediction. 

## Results
- Random Oversampling: ![image](https://user-images.githubusercontent.com/113566508/220238612-4c30c816-157b-40b9-85d0-9b5ec44e61ef.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. 

The precision of the low risk credit applicant was very close to 1, because there were just 35 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is bad, because we are predicting 57 high risk applicants from 92. This means that 38% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is bad, because we are predictiong 6,661 low risk applicants incorrectly as high risk applicants, this means that we are incorrectly not giving a loan to the 39% of the applicants that should receive it. 

### Recall 


- SMOTE: ![image](https://user-images.githubusercontent.com/113566508/220239816-c8bd56aa-ffc3-4034-8702-aa36109feacf.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. 

The precision of the low risk credit applicant was very close to 1, because there were just 37 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is bad, because we are predicting 55 high risk applicants from 92. This means that 40% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is bad, because we are predictiong 5,983 low risk applicants incorrectly as high risk applicants, this means that we are incorrectly not giving a loan to the 35% of the applicants that should receive it. 

### Recall 

- Cluster Centroids: ![image](https://user-images.githubusercontent.com/113566508/220240636-e2b84ba8-f7aa-412a-af00-da0daecc8a0d.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. 

The precision of the low risk credit applicant was very close to 1, because there were just 38 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is bad, because we are predicting 54 high risk applicants from 92. This means that 41% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is bad, because we are predictiong 9,881 low risk applicants incorrectly as high risk applicants, this means that we are incorrectly not giving a loan to the 58% of the applicants that should receive it. 

### Recall

- SMOTEENN: ![image](https://user-images.githubusercontent.com/113566508/220240947-efaba62f-eb68-4fe2-a460-82602c06721f.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. 

The precision of the low risk credit applicant was very close to 1, because there were just 26 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is better than the the last ones, because we are predicting 66 high risk applicants from 92. This means that just 28% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is bad, because we are predictiong 7,404 low risk applicants incorrectly as high risk applicants, this means that we are incorrectly not giving a loan to the 43% of the applicants that should receive it. 

### Recall


- Balanced Random Forest Classifier: ![image](https://user-images.githubusercontent.com/113566508/220235475-59873341-aa77-4c3a-a2f3-1e15d2c7c753.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. 

The precision of the low risk credit applicant was very close to 1, because there were just 31 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is bad, because we are predicting 61 high risk applicants from 92. This means that 34% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is high (0.89), this means that we predicted 15,193 low risk applicants from 17,113 low risk applicants. 

### Recall 

- EasyEnsembleClassifier: ![image](https://user-images.githubusercontent.com/113566508/220242688-375b1783-8bf2-44d8-aaeb-4fc777bb4d6f.png)

### Precision
The precision of the high risk credit applicants was low, which means that there were many low risk applicants predicted as high risk applicants, this is not so influential. It is not as low as the others, but this is not important in this case. 

The precision of the low risk credit applicant was very close to 1, because there were just 8 high risk applicants predicted as low risk. 

### Sensitivity
For this prediction we want to make, the sensitivity is more important because we prefer to have low risk applicants predicted as high risk applicants, than high risk applicants as low risk. 

The sensitivity for the high risk applicants is the best one yet, because we are predicting 84 high risk applicants from 92. This means that just 9% percentage of the high risk applicants are receiving their loan. 

The sensitivity for the low risk applicants is the best one yet, this means that we predicted 15,999 low risk applicants from 17,113 low risk applicants, this means that we are incorrectly not giving a loan to just the 7% of the applicants that should receive it. 

### Recall 

## Summary




