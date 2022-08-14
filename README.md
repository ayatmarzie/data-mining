# data-mining
This project contains three phases: preprocessing, classification, and clustering. "PTJ4_Ayat" includes these phases. In the excel file, we have information about each activity of absence, and our target column is Absenteeism time in hours. First, it prints numeric features' mean, range, and variant. 
In the next cell, we have each feature's missing value percentage. The guideline has asked that if any column had lost more than 30 percent of its values, you should ignore that, but no such thing exists.

For the following seven cells, we fill in missing values. There are many ways to fill missing values like regression, mean, and average of that feature. But in this file, the features are information about a person, and the ID of each person is unique. Also, some people have multiple absences, so we can use the previous sample to fill empty cells. Fortunately, this technique helps me to fill all the null values. We can run cell 40 again to see how many missing values remain. If there are still some, we can use the average to fill that.
Then we can use quartile to omit outliers. The first and last quartiles are deleted, and only the two interquartile have remained unchanged(not deleted).
In the next 11 cells, the target column and some random features have been chosen to plot.
In the next cell, an output file will produce.
The following cell would delete all the samples which have meaningless target columns. A zero target feature means the person has an absence which is less than 1 hour, and it is not essential for us.
#in the next few cells, we train data with classification techniques
In the next cell, we make the data ready for classification, which means we model them in a classification model, so we make the data in two categories of being less than 24 or not.
Then, we use k-fold crossing(k=10) for KNN and find the best K for KNN, which is 3 in this case.
Then it makes the decision tree.
Then we train data with the bagging classifier.
Then we measure the confusion matrix and evaluate performance.
#In the following cells, we use clustering techniques to train data.
We train data with kmediod and kmean.
Then we use the elbow method to find the best k( optimized k) for kmean, which is 11 in this case.
#test cell
Using PCA, data was shown in 2 dimensions, and each cluster was printed with unique color.
We evaluate the performance of both supervised and unsupervised.
