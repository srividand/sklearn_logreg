# sklearn_logreg

**Project Statement:** Using scikit learn perform classification using logistic regression and SVM classifier.

Firstly, I imported the data using read.csv and printed the basic stats of the variables using describe() function.

There are two dependent variables and all are independent variables. So, using matplotlib I printed the histogram of all the independant variables.

And I split the data into 70% training and 30% testing data, and performed logistic regression for both training and testing data and I performed the metric AUC and its 0.82.

Then, I did another classification using SVM algorithm. I used SVC function and tuned hypermeter from 0.1 to 1.0 using forloop and did the validation metric and AUC. The AUC is 0.87.

The AUC score when C =1 is 0.87, which is greater than any c value. So, C = 1 value gives the optimal SVM classifier with respect to AUC.

Hyperparameter C: The Regularization parameter (often termed as C parameter in python’s sklearn library) tells the SVM optimization how much you want to avoid misclassifying each training example.

For large values of C, the optimization will choose a smaller-margin hyperplane if that hyperplane does a better job of getting all the training points classified correctly. 

Conversely, a very small value of C will cause the optimizer to look for a larger-margin separating hyperplane, even if that hyperplane misclassifies more points.
