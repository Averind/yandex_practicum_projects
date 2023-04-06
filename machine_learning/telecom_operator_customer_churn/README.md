**Project 'Prediction of customer churn in a mobile operator'**

Machine learning models were trained based on customer data of a mobile operator. The goal was to build a classification model that predicts whether a customer will leave the telecommunications operator or not.

During the project, Decision Tree, Random Forest, Logistic Regression, LGBM, and Cat Boost models were trained, which showed the following results:

|Model|AUC-ROC|
|----|----|
|Decision Tree|0.81|
|Random Forest|0.82|
|Logistic Regression|0.83|
|LGBM|0.90|
|Cat Boost|0.83|

The best model was the LGBM Classifier, which had the highest AUC-ROC value. This model was tested on a test set, and the AUC-ROC value was 0.916.

An experiment was also conducted: the LGBM Classifier model was trained on a training set consisting of only the two best parameters. On a similar test set with the same features, the model showed an AUC-ROC value higher than on the full dataset, specifically 0.919.
