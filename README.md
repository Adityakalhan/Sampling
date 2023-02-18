# Sampling

Without any data preprocessing, the precision, recall and f1 score for class 1 was coming out to be 0 in every model. <br>

## Simple Random Sampling
Here, every individual is chosen entirely by chance and each member of the population has an equal chance of being selected. Simple random sampling reduces selection bias. Simple random sampling reduces the chances of sampling error. Sampling error is lowest in this method out of all the methods. <br>

#### With replacement 
With replacement, LightGBM and Random Forrest classifiers gave accuracty of 100% while Bagging Classifier gave an accuracy of 99% (0.99 f2 score for class 0 and class 1).
It proved to be to the most effective appraoch for this particular dataset. <br>
#### Without replacement
Artificial data points were made using SMOTE and the minority class was made to have the same number of data points as the majority.
In this approach, Lightgbm and Random Forest had f1 scores of 0.99 while Bagging Classifier had f1 scores of 0.98 for each class.

## Sytematic Sampling
Systematic sampling is a statistical method that researchers use to zero down on the desired population they want to research. Researchers calculate the sampling interval by dividing the entire population size by the desired sample size. Systematic sampling is an extended implementation of probability sampling in which each member of the group is selected at regular periods to form a sample.<br>

Since the dataset was small, it didn't work at all and the f1 scores for class 1 was 0 for for all classifiers.

## Cluster Sampling
In a clustered sample, we use the subgroups of the population as the sampling unit rather than individuals. The population is divided into subgroups, known as clusters, and a whole cluster is randomly selected to be included in the study. This type of sampling is used when we focus on a specific region or area.<br>

Since the dataset was small, it didn't work at all and the f1 scores for class 1 was 0 for for all classifiers.
