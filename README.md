# Random-Forest-Classifier

A very simple Random Forest Classifier implemented in python. The sklearn.ensemble library was used to import the RandomForestClassifier class. The object of the class was created. The following arguments was passed initally to the object:

 - n_estimators = 10
 - criterion = 'entropy'

The inital model was only given 10 decision tree, which resulted in a total of 10 incorrect prediction. Once the model was fitted with more the decision trees the number of incorrect prediction grew less.

It was found that a the optimal number of decision trees for this models to predict the answers was 200 decision trees. Hence the n_estimator argument was given a final value of 200.

Anything more that 200 will result in over-fitting and will lead further incorrect prediction.
