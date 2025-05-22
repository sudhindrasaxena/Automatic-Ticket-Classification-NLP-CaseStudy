# Natural-Language-Processing-Case-Study---Automatic-Ticket-Classification

## Problem Statement
For a financial company, customer complaints are a crucial indicator of potential issues in their products and services. Resolving these complaints efficiently not only minimizes customer dissatisfaction but also helps retain customers and build loyalty. Additionally, analyzing complaint data provides actionable insights to improve services and attract new customers.

However, these customer complaints are typically unstructured text data. Traditionally, companies employ teams to manually evaluate and route each complaint ticket to the appropriate department. As the company grows and the volume of tickets increases, this manual process becomes unsustainable and error-prone.

This case study simulates the role of an NLP Engineer tasked with automating the classification of support tickets for a financial firm offering services such as credit cards, banking, and mortgages/loans.

## Business Goal
The goal is to build an automated ticket classification system that categorizes customer complaints based on the product or service involved. Automating this classification process enables:

* Faster issue resolution
* Efficient ticket routing
* Better resource allocation
* Enhanced customer experience

## Dataset

The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.

## Expected tasks
We need to perform the following eight major tasks to complete :

* Data loading
* Text preprocessing
* Exploratory data analysis (EDA)
* Feature extraction
* Topic modelling 
* Model building using supervised learning
* Model training and evaluation
* Model inference



**Note**: Once you have finalised the clusters/categories for customer complaints, the next step is to create a data set that contains the complaints and labels (which you found using NMF). This labelled data set will be used for model building using supervised learning. 

* You need to try at least any three models from logistic regression, naive Bayes, decision tree and random forest. 
* You need to select the model that performs the best according to the evaluation metrics.
