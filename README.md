# credit_card_fraud_unsupervised_machine_learning
The dataset is hosted at kaggle.  
https://www.kaggle.com/mlg-ulb/creditcardfraud

Credit card transation data from Europe in 2013 were logged and pre-precessed by PCA.  
Among 284K transactions, there are only 492 frauds.  Therefore, the dataset is very unbalanced.  

I use the SMOTE to oversample the minor group so that the data can be used for supervised machine learning. 
For unsupervised machine learning analysis, the random undersampling from sklearn is applied. 

I was able to achieve 89% fraud detection using supervized machine learning.
