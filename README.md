## Breast-Cancer-Detection
# Working Procedure: 
● Import libraries such as numpy and pandas
● Import dataset
● Getting the information about the dataset such as columns, rows.
● Data cleaning or preprocessing which includes dropping columns with duplicate
patient ids.
● Splitting dataset into training and testing model- creating a separate 2D array x which
includes some parameters which determine the result. The result is made into a
separate 2D array y. The testing and training models are also defined in x and y, and
the testing size is taken to be 20 per cent of the overall dataset. The rest 80 per cent is
the training dataset.
● Importing KNN model from sklearn library.
● Applying KNN model to dataset
● Creating a KNN classifier instance for the training models in x and y.
● Importing accuracy score attribute of sklearn.metrics.
● Calculating the accuracy score using the predicted values of y and the testing set of y
as the two arguments.
● Applying Logistic Regression model to dataset and calculating its accuracy score
● Applying Naïve Bayes model to dataset and calculating its accuracy score
● Applying K Cross Validation model to dataset and calculating the cross validation
accuracy of all the models.
# Learning Outcomes: 
● Learning the usage of important libraries such as NumPy and Pandas and how to get
information about the dataset, such as the number of rows and columns.
● We developed a model with high accuracy to correctly classify between malignant and
benign tumours and minimizing errors during the classification.
● Applying different machine learning models such as logistic regression and Naïve
bayes model on the dataset and calculating the cross-validation accuracy of all of
these models.
● Learning how to divide the dataset into training and testing sets and performing
operations on the training dataset.
● Learning how to use metrics such as accuracy score to determine the accuracy of the
model on the testing set.
● Doing a comparative analysis of the accuracy of the different machine learning models.
