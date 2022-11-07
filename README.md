# Supervised-Machine-Learning-Challenge

## Background: 
Supervised learning, as the name indicates, has the presence of a supervisor as a teacher. Basically supervised learning is when we teach or train the machine using data that is well labelled. Which means some data is already tagged with the correct answer. After that, the machine is provided with a new set of examples(data) so that the supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labelled data.

Supervised learning is classified into two categories of algorithms: 

Classification: A classification problem is when the output variable is a category, such as “Red” or “blue” , “disease” or “no disease”.
Regression: A regression problem is when the output variable is a real value, such as “dollars” or “weight”.

Supervised learning deals with or learns with “labeled” data. This implies that some data is already tagged with the correct answer.

Types:-

Regression
Logistic Regression
Classification
Naive Bayes Classifiers
K-NN (k nearest neighbors)
Decision Trees
Support Vector Machine

Instructions: 

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. This data will be used to
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

In this assignment, you will be building a machine learning model that attempts to predict whether a loan will be approved or not.

## Consider the models

You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

## Fit a LogisticRegression model and RandomForestClassifier model

Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.

# Analysis: 

My predictions were that Random Forest Model Classifier Model will yield better results. After fitting the models, splitting the data and printing the model scores. It can be concluded that both models performed well and yielded similar results. The model score for the Logistic Regression Model came out to be 0.9924680148576145 approximately 99% and the model score for the Random Forest Classifier model came out to be 0.9914878250103177 which is approximately 99%. Both models predicted values came out to be the same as their actual values. 


# Reference: 

* The background and theory for Supervised Learning was taken from [GeeksForGeeks](https://www.geeksforgeeks.org/supervised-unsupervised-learning/)