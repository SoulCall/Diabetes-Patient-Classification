## Team Members

The team has two members: Andrea Clark Sevilla (aclarkse@ur.rochester.edu) and Jonathan Yakubov (jyakubov@ur.rochester.edu).

## Instructions

Make sure to specify the file path in the variable `data_path` declared at the beginning of the `diabetes_preprocessing()` function definition. The script is thoroughly commented for easy use. However, a brief outline of our work will be presented below:

## Data Preprocessing

The first function, `diabetes_preprocessing` loads the data file into a pandas dataframe and cleans and preprocesses the data. The processed data is returned as a pandas dataframe, `diabetes`.

## Oversampling

This portion of the code was an attempt to improve our models' accuracies by modifying the distribution of the readmitted and non-readmitted classes (the data was biased towards the non-readmitted class). However, this code was not used in the final analysis, as the gains in accuracy using oversampling was either minimal or non-existent for the various models.

## Feature Selection

A Random Forest Regressor was implented using SkLearn to select the most relevant features in our data. The output is a list of the features listed by relevance.

## Apriori

An implementation of the Apriori algorithm using the Apyori Python library. The output is a list of the frequent itemsets using a minimum support of 0.5 and a max length of 5.

## Naive Bayes'

An implementation of a Naive Bayes' classifier using SkLearn.

## SVM

An implementation of a Support Vector Machine using SkLearn.

## Neural Network

An implementation of a Neural Network using SkLearn, Keras, TensorFlow, and Theano.