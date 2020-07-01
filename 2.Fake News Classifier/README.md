# Fake News Classifier Using TF IDF


## Fake News Classifier

Dataset: https://www.kaggle.com/c/fake-news/data#

## Objective

Develop a machine learning program to identify when an article might be fake news. Run by the UTK Machine Learning Club.

## Evaluation

The evaluation metric for this competition is accuracy, a very straightforward metric.

accuracy=correct prediction/(scorrect predictions+incorrect predictions)
Accuracy measures false positives and false negeatives equally, and really should only be used in simple cases and when classes are of (generally) equal class size

## Data Description

train.csv: A full training dataset with the following attributes:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable
test.csv: A testing training dataset with all the same attributes at train.csv without the label.

submit.csv: A sample submission that you can


# Model Description

Model Trained on independant variable 'text' in the dataset. Using various Machine Learning Algorithms as follow:
1. MultinomialNB Algorithm : 0.8810273405136703 Accuracy

2. Passive Aggressive Classifier Algorithm : 0.918 Accuracy

3. Multinomial Classifier with Hyperparameter :
Alpha: 0.0, Score : 0.8662800331400166
Alpha: 0.1, Score : 0.8777133388566695
Alpha: 0.2, Score : 0.8801988400994201
Alpha: 0.30000000000000004, Score : 0.87986743993372
Alpha: 0.4, Score : 0.8808616404308203
Alpha: 0.5, Score : 0.8806959403479702
Alpha: 0.6000000000000001, Score : 0.8815244407622204
Alpha: 0.7000000000000001, Score : 0.8813587406793704
Alpha: 0.8, Score : 0.8816901408450705
Alpha: 0.9, Score : 0.8816901408450705

4. HashingVectorizer : 0.871 Accuracy
