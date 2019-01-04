# Credit-Card-Fraud-Detection
Using Deep learning (Artificial Neural network ) we are detecting fraud transaction  using anonymized data.
As such data is highly biased (fraud transactions are less than 0.1 % in real life )  ,
we are using smote to over-sample the data .

Libraries needed :
1. Numpy
2. Pandas
3. Keras
4. imblearn
In cases of highly baised data such as bank transaction,one class (fraud transactions , in this case ) very few.
As a result , Model is not well trained for detecting observation for that class .
In such cases ,either we can use undersampling or Oversapmling.
We chose Oversampling using Smote .

There are other ways to handle such datasets .
Ensemble methods are found to good for handling imbalance data. 
Random forest is found to be good at handling imbalance data.
 In this code , you can observe that ,we are getting better accuracy and loss with out smote but ,
 when we use the models to predict for whole dataset , we got better results  with deeplearning +smote in detecting Fraud detection.
 
Refer :
https://medium.com/coinmonks/smote-and-adasyn-handling-imbalanced-data-set-34f5223e167
