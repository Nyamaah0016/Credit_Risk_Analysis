# Credit Risk Analysis with Supervised Machine Learning

### Overview
Credit risk is one of the important job to be performed by credit risk analyst to identify a risk involved in the loan being disbursed to an individual. There are various techniques available by the help of which we can train and evaluate a model with unbalanced classes. Following are some of the libraries and algorithms which are used to build and evaluate models using resampling: imbalanced-learn, scikit-learn, RandomOverSampler, SMOTE algorithms, ClusterCentroids algorithm, SMOTEENN algorithm, BalancedRandomForestClassifier (bias reduction model), EasyEnsembleClassifier (bias reduction model)

### Purpose
The purpose of the model is to explain how a machine learning algorithm is used in analyzing the data, create a training and test groups, execute various machine learning algotithms like logistic regression, decision tree, random forest, and support vector machine algorithms, interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms, compare the advantages and disadvantages of each supervised learning algorithm, determine which supervised learning algorithm is best, use ensemble and resampling techniques to improve model performance

### Result
Machine Learning Models with balanced accuracy, precision and recall score:
- Naive Random Oversampling : Accuracy (0.6612700484668286), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall (High/Low risk = .66/.67)
- Undersampling : Accuracy (0.6303296388959394), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall(High/Low risk = .63/.40)
- Combination Under Over Sampling : Accuracy (0.5173713090878325), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall (High/Low risk = .70/.57)
- SMOTE : Accuracy (0.6303296388959394), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall (High/Low risk = .62/.64)
- Balanced Random Forest Classifier : Accuracy (0.7877672625306695), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall (High/Low risk = .67/.91)
- AdaBoost Classifier : Accuracy (0.925427358175101), Precision (The precision is low for High-risk loans and is high for Low-risk loans), Recall (High/Low risk = .91/.94) 

### Summary
For the analysis we can see that easy ensemble adaboost classifier is the best model. The reasons are as follows:
- The accuracy of a machine learning model lies between 0 and 1 (1 being the best), in case of adaboost classifier it is .93
- Precision for all the models are similar and within the range
- The accuracy of a machine learning model lies between 0 and 1 (1 being the best), in case of adaboost classifier it is the highest
