# Classification-of-Japanese-Population-using-Individual-as-well-as-Stacked-Models

In this project, we analyse the factors of the Japanese Census with respect to the dual genders of the Japanese population - either Male or Female. Hence, this is considered to be a binary classification problem. The features in the dataset are 'Age Upper Bound', 'Age lower Bound', 'Prefecture', 'Year', 'Gender' and 'Population'. 
The models considered for stacking are:
Base Models: SVM Classifier, Decision Tree Classifier, KNN Classifier, Naive Bayes Classifier
Meta Model: Logistic Regression for binary classification

After running the model for different train and test splits of the datasets,  we can conclude that, knn is the best classifier model with the least mean, whereas svm classifier gives the least desirable performance.
Also, logistic regression and naive bayes classifiers underfit the data, whereas svm, knn, decision tree and the stacked model overfit the dataset.
Logistic Regression have the highest probability of producing outliers, whereas knn has the least probability of producing outliers.
For train-test split at 40%-60% of the dataset, produces the most outliers for all models, the most for the stacked model
