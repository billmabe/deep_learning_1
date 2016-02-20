# deep_learning_1

This file contains the code for a deep learning project using h2o for R.

1. h2o parameter tuning using grid search. This is a little exercise to identify the "best" parameters for a deep learning model based on the mean squared error. I wondered: would one set of parameter values consistently have a lower mse than all the other sets, across multiple values of nfolds. That would be a pretty robust set of parameters. Instead, what I found--in this example--is that depending on the value I selected of nfolds, different sets of parameters would "win." I created a function to conduct the grid search, ran it in a loop to populate a list, calculated the mse for each folds level (i.e., each element in the list), plotted it using ggplot2. The plot best illustrates how the mse values of the different parameter sets vary by nfolds.
2. 

