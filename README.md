# hyperparameter-optimization-of-NN-using-kerastuner

**First of all You can download the dataset from this link https://www.kaggle.com/mlg-ulb/creditcardfraud .**

**Requirement:
pandas,
numpy,
matplotlib,
seaborn,
tensorflow or keras,
keras tuner for hyperparameter tuning,
sklearn for ML part,
imblearn.**


**To make this imabalnced dataset into balanced dataset i used oversampling using imblearn library and later for training purpose i used hyperparameter tuning of Neural Network with the help kerastuner and i compare accuracy of N.N with the accuracy of Randomforest Ml algorithm in the end i came to the conclusion that both performed well but  i used minmax scler to scale down the dataset records for N.N and in case of randomforest we dont need to scale down the dataset record because it is ensemble algorithm and it used decision tree internally for training**
