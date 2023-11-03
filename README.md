# SVM Disaster Tweet Classification

## About This Ptoject

This project is a project that aims to classify whether a tweet is a tweet that contains information about disasters or not. This project is also an experiment from a research that I worked on with my lecturer who utilised the SVM algorithm to perform classification by trying to modify the kernel value (linear, poly, rbf, sigmoid) and C parameter. Later, the model with the best parameters will be taken which has the highest accuracy in classification.

## About Disaster Tweet Dataset

[**Disaster Tweet Dataset**](https://www.kaggle.com/competitions/nlp-getting-started/data) is a dataset that contains tweets accompanied by a label whether the tweet contains information about a disaster event or not.

**Dataset Information**

* id : data index
* keyword : keyword from the tweet (may be blank)
* location : the location the tweet was sent from (may be blank)
* text : the tweet
* target : the label of the tweet, 1 means it contains disaster information and 0 means it does not contain disaster information.