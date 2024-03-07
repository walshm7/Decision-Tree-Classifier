# Decision-Tree-Classifier
An ML model that predicts the value of a target variable based on input features. Recursively partitioning the data into subsets based on the features, creating a tree-like structure of decisions. Used datasets of 4898 and 1599 points for training and testing respectively.

For evaluating the best splits use the information gain based on the entropy before and after the split.

Take as input the dataset, the minimum node size η and the minimum purity π, and prints out the decision tree with each child indented and aligned, as noted next. 

For printing the decision tree it is generated on the Iris Dataset which has 150 points from three types of Iris flowers. The decision tree, with η=5 and π=0.98.
