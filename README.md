# petfinder.my-

### Project overview

Millions of stray animals suffer on the streets or are euthanized in shelters every day around the world. If homes can be found for them, many precious lives can be saved — and more happy families created.

In this Project i will uncover the Secrets behind pet adoption.

### Project Goals

* Extract insights about what makes pets more likely adopted.
* Build a model that will predict adoption speed for pets 
* Perform some data cleaning, try out multiple ML models.

### Models Used

* Random Forest Classifier
* Decision Tree Classifier
* Logistic Regression
* Support Vector Classifier
* Gradient Boost Classifier

### Results and Conclusion

The shortest predict time was achieved with Logistic Regression with hyperparameter tuning, while Gradient Boost Classifier using smote sampling had a good score on test and train kappa but performed poorly on the leaderboard.

The Gradient Boost Classifier without hyperparameters performed best on the leader board achieving a score of `0.23040`.  The baseline Logistic Regression model had a score of `0.18179`.

Overfitting was observed for Random Forest and Decision Tree classifier with and without optimization. Reducing the number of features addressed the overfitting slightly for the 2 models.
