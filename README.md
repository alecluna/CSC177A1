# CSC177 Data Science/Data Mining #
Made by Josh Singh & Alec Luna

## Project One: ##

In this project we practiced with data cleaning and analytics using Pandas and Numpy.
We analyzed a large Twitter dataset collected during the 2016 US presidential election,
processing tweets by location, user and hashtags/mentions. We ordered tweets by the most occurrences.

## Project Two: ##

In this project we used the cleaned data from Project 1 to practice with three Clustering algorithms:
k-means, MAX-based agglomerative clustering, and SSE-based agglomerative clustering. 

## Project Three ##

In this project, we used the original data from Project 1 to practice with algorithms for classification.
The goal of this project was to create classification models that predict if a user is a follower of Trump or Clinton. 
In the file “clinton_trump_user_classes.txt”, we have the ground truth “class” membership for each user id in the data. 
Class 0 corresponds to Trump followers, while class 1 corresponds to Clinton followers.
The classification algorithms we used were: Decision Tree, SVM, Logistic Regression, and a Neural Network.
We also used a k-NN model with 5-fold cross validation, however this proved to be difficult to implement succesfully since
it ran for long periods of time on our machines. 
