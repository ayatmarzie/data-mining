# data-mining
This project contains three phases: preprocessing, classification, and clustering. "PTJ4_Ayat" includes these phases. In the excel file, we have information about each activity of absence, and our target column is Absenteeism time in hours. First, it prints numeric features' mean, range, and variant. 
In the next cell, we have each feature's missing value percentage. The guideline has asked that if any column had lost more than 30 percent of its values, you should ignore that, but no such thing exists.

for the next seven cells we fill missing values. there are many ways to fill missing values like regression, mean and average of that feature. but in this file the features are information about a person and the ID of each person is unique and also some people has multiple absence so we can use the previous sample to fill empty cells. Fortunately this technique helps me to fill all the null values. we can run cell 40 again to see how many missing values remained. if there is still some we can use average to fill that.
then we can use quartile to omit outliers. the first and last quartile are deleted and only the two interquartile is remained unchanged(not deleted).
