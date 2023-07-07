# Gini-AND-Entropy
Apply the two methods with DT classifier and compare their results.

# Result
From the above predictions of both the decision tree classifier models, we can see that " CP " is the root node indicating that "CP" is the main factor that impacts heart disease in a patient. 

The internal working of both methods is very similar and both are used for computing the feature/split after every new splitting. But if we compare both the methods then Gini Impurity is more efficient than entropy in terms of computing power and shorter period of excution time . 

The range of Entropy lies in between 0 to 1 and the range of Gini Impurity lies in between 0 to 0.5. Hence we can conclude that Gini Impurity is better as compared to entropy for selecting the best features. 

The predictions change according to the data and also the train_test_split percentage and even the bias and variance in data would have an impact. 

To increase the accuracy, we can split the dataset in to many small datasets and create models and again consolidate the results to get an optimum accuracy. 
