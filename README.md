# IMDB_SentimentAnalysis
Classification analysis to predict a movie positive/negative review from a trained model of IMDB reviews, using Recurrent Neural Networks (RNNs)

This is a project assignment from **Udacity Deep Learning Nanodegree program**.

The project trains a Long short-term memory (LSTM) type of RNN, to classify a positive or negative evaluation from thousands of user reviews of IMDB movies.

The trained model is deployed to an instance in *AWS Sagemaker*.

A sample web application uses the deployed model to predict a positive or negative evaluation from a user input review text.

### Data requirements:
-  [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

### Library Requirements:
- os
- glob
- sklearn
- nltk
- re
- bs4
- pickle
- collections
- numpy
- pandas
- sagemaker
- torch

AWS permissions to use S3 and Sagemaker.
