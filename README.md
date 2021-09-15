# QBUZZ-ML-Hackathon
A bunch of colab files I used to experiment to achieve the highest classification accuracy for my multiclass classification problem. 

Training data: Given a set of features about a crop, determine is still usable, should be removed or fresh. Its a multiclass classification problem. 

Caveat: The dataset is highly imbalanced. This results in multiple misclassifications: Predicing the minor class as the major class. Also, there are multiple missing values in the dataset. 

Approach: Experimented with median imputation and other techniques to address the missing values. I normalized the data and have tried to balance the dataset by generating synthetic exmaples for classes with less examples. Used the training set and trained a bunch of algorithms to check which fetches me the best accuracy. I have experimented with decision trees, logistic regression, random forest, SVM, ensemble of ML algorithms, XGBoost, Catboost etc. Performed hyper parameter optimization for each algorithm to find the best set of paramters which can give me the best classification accuracy and least mlogloss. Ensured that the model is not overfitting my examining and keeping an eye on training, validation and test accuracy.

Result of the competition: Finished 7th in the competition in the end with a multiclass classification accuracy of 86.68%. The link to the certificate can be found https://cdn.skillenza.com/certificates/Qwp2q15UtNUF.png
