# ml-01
Project ml-01 was developed in order to understand how Support Vector Machines work, especially the difference between the various kernels that can be used and the models' parameters. The classifiers used were: Logistic Regression, SGD Classifier, Support Vector Classifier with Linear, Polynomial, RBF, and Sigmoid kernels.

The project was divided in 7 main parts, with steps 3, 4, and 5 being repeated for each different classifier:

1. Load the data, analyze the data by printing the DataFrame schema, shape, column statistics, class label distribution, and missing values count.
2. Preparing the data, such as by dropping the index column and using integer encoding to convert string values to integer values. Using the 70/30 hold-out method for train and test set separation, the stratified split method was used. 
3. Train the classifier.  
4. Test the classifier and show the confusion matrix, accuracy, precision, recall, and F-1 score.
5. Plot the precision and the recall.
6. Due to the SVC Classifier's bad performance with the Sigmoid kernel, an improvement on the classifier is needed. Such improvement was accomplished by peforming data processing before training (data scaling) and fine-tuning the C parameter.
7. Perform 3-fold cross validation in all the classifiers and print the results to the screen, showing the CV results keys, the test scores, the mean of the test scores, the CV scores mean, and the CV scores standard deviation.
