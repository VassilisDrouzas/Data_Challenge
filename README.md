# Data_Challenge


The goal of this project is to study and apply machine learning/data mining techniques to a real-world
classification problem. In this classification problem, each sample corresponds to a domain name and
the task is to assign each domain name into a predefined category (i.e., class).

In the context of this project, we are given both a web graph consisting of several thousands of greek
domain names, and the textual content of the webpages of a subset of these domain names. The task
is to build a model for predicting the class label of each domain name.

Our goal is to learn the parameters of a classifier from a collection of training products (with known class
information) and then to predict the class of unlabeled products.
The challenge is hosted on Kaggle, a platform for predictive modelling on which companies, organizations and researchers post their data, and statisticians and data miners from all over the world
compete to produce the best models.

The performance of the models is assessed using the multi-class logarithmic loss measure. This
metric is defined as the negative log-likelihood of the true class labels given a probabilistic classifier’s
predictions.

In this challenge, we tried to incorporate both text and graph features. The main classifiers we tested are:

1) BERT
2) GCN
3) GraphsAGE

![Screenshot (95)](https://github.com/VassilisDrouzas/Data_Challenge/assets/81232757/6018ab91-e353-4913-b88f-5a17ffcde007)
