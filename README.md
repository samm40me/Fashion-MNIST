# Fashion-MNIST
The objective is to build a classifier to >90% accuracy on the test set

## Description
In most real-world applications, labelled data is scarce. Suppose you are given
the Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist), but without any labels
in the training set. The labels are held in a database, which was querried to
reveal the label of any particular image it contains.

## Task
The task is to build a classifier to >90% accuracy on the test set, using the smallest number of queries to this >database. 

## Approach
A combination of supervised and unsupervised techniques and CNN were used. 

## Principal Component Analysis on the Fashion MNIST Data
With Principal Components (PCs) analysis I hope to find PCs that allow me to represent the most samples with much less dimensions. I performed PCA the data by using the PCA class from sklearn.

