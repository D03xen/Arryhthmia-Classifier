# Arrythima-Classifier
Dataset used in this project is available on the UCI machine learning Repository. 

• It can be found at the following address: https://archive.ics.uci.edu/ml/datasets/Arrhythmia. 


• It consists of 452 different examples spread over 16 classes. Of the 452 examples, 245 are of "normal" people. We also have 12 different types of arrhythmias. Among all these types of arrhythmias, the most representative are the "coronary artery disease" and "Rjgbt boundle branch block".


• We have 279 features, which include age, sex, weight, height of patients and related information from the electrocardiogram. We explicitly observe that the number of features is relatively high compared to the number of examples we are available.


• Our goal is to predict if a person is suffering from arrhythmia and if class, classify it in to one of 12 available groups.

Imputation was done both with Mean and Mode and same best recall score of 99.5290 was obtained with Random Forest Classifier and Kernelized SVC using PCA and oversampling.
