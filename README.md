# Implementing-Gradient-Descent-from-Scratch
Implemented Gradient Descent Algorithm from scratch.
In this project, I have collected the datasets of Comment Volume prediction on Facebook post in H hours.I have collected the dataset from UCI Database.
The datasets have 5 training sets and 1 test set. To get unbiased result, I have merged all the datasets into one and then splitted it into Train and Test (70/30 ratio).
The Comment volume dataset (csv with ‘,’ delimited) is a multi variate dataset. It has 612857 observations and 53 features. Out of 53 features, 14 are categorical variables. Memory usage is 257.2 MB. There are no missing values in the dataset.
In the dataset there are essential features (C1 to C5) which is holding the values of the number of comments of a post with reference to a base time.
C1: Total number of comments of a post in the last 48 hours from the base time.
C2: Total number of comments of a post in the last 24 hours from the base time.
C3: Total number of comments of a post in the last 48 hours to last 24 hours with respect to the base time.
C4: Total number of comments of a post after 24 hours of its published time and it is assumed that the published time is a time which is before Base time.
C5: It is a derived field. It is the difference of C2 and C3.

Here in the attached code, I have played around with threshhold value for convergence and Learning rate.
The code has functions written for 
1>  Cost value calculation.
2>  Gradient Descent Calculation.
3>  RMSE Calculation.
4>  R2 Calculation block.
