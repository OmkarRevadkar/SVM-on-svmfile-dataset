SVM (Support Vector Machines) is a supervised learning classification algorithm. It is used to segregate classes and it then applies probability for the classes to give the final prediction. SVM is preferable when the target variable is categorical and when the data set is very very large i.e when the data is a high dimensional data. 

We will choose a kernel or boundary line (SVM hyperparameter) which is farthest away even from the nearest point so that the probabilities are quite differentiable and final predictions are easy to make for the machine. Hence, decision making on SVM model will be much more easier.

Interestingly, SVM can also be used in case of regression problems but the best results are found with classification problems.

Keeping in view the problem statement, since customers are our target in this dataset, we will prioritily consider precision score while evaluating the model.
As in this project, class imbalance was also found and hence oversampling was done on train data after normal sampling. But on oversampling, while other parameters improved, precision score got signficantly reduced than that what it was before oversampling. So we will choose a model which was built before oversampling on a concluding note.





