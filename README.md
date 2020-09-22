# Spam NonSpam Email Classification Using Linear discriminant analysis(LDA)

The aim is to create a classifier that can separate spam from non-spam emails i.e binary classification.

## About Data
The dataset and short descriptions about the variables in the dataset are available from the following data 
archive: https://archive.ics.uci.edu/ml/datasets/spambase


## Steps Involved

1. Identified top 10 predictors for which the difference between the spam-class average and non- spam class average is highest
2. Used linear discriminant analysis to build this classifier
3. Evaluated effectiveness of model using confusion matrix, lift chart and decile chart
4. Changed the probability threshold of 0.2, to see if the accuracy increases

### Linear Discriminant Analysis(LDA)
LDA is a common technique used for supervised classification problems.It is a myth that LDA is just used for dimensionality reduction but linear discriminant analysis is not just a dimension reduction tool, but also a robust classification method.
With or without data normality assumption, we can arrive at the same LDA features, which explains its robustness.

The Big Picture
• To classify a new record, measure its distance from the center of each class
• Then, classify the record to the closest class
Here we can measure the distance with Euclidean distance,Mahalanobis Distance etc each has its own pros and cons.


For code refer to the R markdown file(Rmd)
