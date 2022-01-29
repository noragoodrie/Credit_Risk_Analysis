# Credit_Risk_Analysis

**OVERVIEW**

We used the credit card dataset from LendingClub which is a peer to peer lending services company to complete this project. Within this project we needed to generate 6 different datasets by using imbalanced-learn and scikit-learn libraries to help us with the resampling process. We needed to oversample the data by using RandomOverSampler and the SMOTE algorithms. We also undersampled the data byt using the ClusterCentroids algorithm, which you will see the results below. Lastly, we finished off the project by using the BalancedRandomForestClassifer and the EasyEndsemblus reduce bias as well as, predicting the credit risk. 

**RESULTS: 6 OUTPUTS FROM THE PROJECT**

**NATIVE RANDOM OVERSAMPLING**

The balanced accuracy for the Native Random Oversampling model comes out to be 64%. The high risk precision was very low at about 0.01 while the low risk risk was a steady 1.0! For the recall scores the high risk had a recall score of .62 and the low risk had a score of .68!

<img width="955" alt="Screen Shot 2022-01-29 at 2 31 27 PM" src="https://user-images.githubusercontent.com/91299616/151679660-363e2003-9f0d-402b-93f3-e0af13df01ee.png">

**SMOTE OVERSAMPLING**

Our SMOTE algorithm came to have a balanced accuracy score of 64 percent!Our high and low risk presion came out to be the exact same as our Native Random Oversample. High risk recall was .63 while our low risk recall was .66!

<img width="801" alt="Screen Shot 2022-01-29 at 2 37 53 PM" src="https://user-images.githubusercontent.com/91299616/151679806-0c18ef1a-1d55-4469-882a-1d0623bcf84f.png">

**CLUSTER CENTROIDS UNDERSAMPLING**

The Cluster Centroids balanced accuracy came out to be about 64% which is the same as both the results above! The precision for high risk was .01 and low risk cam eout to be 1.0 which is also the same as the above results. The recall for the high risk was .59 and the low risk recall came out to be .44!

<img width="805" alt="Screen Shot 2022-01-29 at 2 41 56 PM" src="https://user-images.githubusercontent.com/91299616/151679893-5afa5ac4-a6b8-4c57-862e-42812688665a.png">

**SMOTEENN OVER SAMPLING**

The smoteenn balance accuracy came out to be 51 percent which is the lowest of all of our results thus far. The high and low precision still match the above results of .01 and 1.0! With a high risk recall of .71 and a low risk recall of .56!

<img width="807" alt="Screen Shot 2022-01-29 at 2 44 53 PM" src="https://user-images.githubusercontent.com/91299616/151679968-38ac1fc3-f845-4803-8ae2-6c2fa5bbb604.png">

**BALANCED RANDOM FOREST**

Our balanced random forest accuracy resulted in a 79 percent results! The precision for high risk was .004 while the low risk was 1.0! Our high risk recall came out to be .67 while our low risk recall cam eout to be .91!

<img width="803" alt="Screen Shot 2022-01-29 at 3 00 28 PM" src="https://user-images.githubusercontent.com/91299616/151680301-c3083ea1-4c65-4e2c-8925-ae06b18b2f46.png">

**Easy Ensemble Classifier**

Our balanced accurary score came out to be 92 percent which is the highest accuracy score we had throughout this project! With a high risk precision of .09 and a low risk of 1.0. While the high risk recall was .92 and a low risk recall of .94!

<img width="800" alt="Screen Shot 2022-01-29 at 3 07 54 PM" src="https://user-images.githubusercontent.com/91299616/151680449-4a6052dd-247e-424e-af20-d6d14ddb4633.png">

**SUMMARY**

According to all of our data outputs it is safe to say that the precision scores for all of the high risk predicitions were very low for all 6 of our results! We can say that the Easy Ensemble Classifer results gave us the highest scores for recall which were .92 and .94! 





