# Machine-Learning-Boosted-Decision-Trees-and-SVM-implementation
•	Predicted whether person’s income is higher or lower than $50k/year based on their attributes
•	Implemented both algorithms (XGBoost and SVM) on a training dataset comprising of 32,561 samples and 123 features by calibrating hyperparameters (like max depth, lambda; C, gamma)
•	Achieved accuracies of over 85% for both algorithms on a testing dataset with 16,281 samples

We will be working on the Adults Data Set, which can be found at the UCI(University of California, Irvine) Website.
Extraction of dataset was done by Barry Becker from the 1994 Census database.  

The dataset uploaded in this repositery is stored in two different files (a9a.txt containing the training dataset  of 32,561 samples and 123 features, a9a.t containing the testing dataset with 16,281 samplesand 123 features) both formatted in LibSVM format. 

The original Adult data set has 14 features, among which six are continuous and eight are categorical. In this data set, continuous features are discretized into quantiles, and each quantile is represented by a binary feature. Also, a categorical feature with m categories is converted to m binary features. 
