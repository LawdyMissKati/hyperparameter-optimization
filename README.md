# hyperparameter-optimization
Using K-Fold cross validation to optimize hyperparameters

Using the movie reviews classification data (covered in the last lab session), use 4-fold cross validation to identify the best hyper-parameters. You need to consider the following options:

1. 3 options for the number of hidden layers:
  a. 1 layer (1 node)
  b. 2 layers (16 nodes, 4 nodes)
  c. 4 layers (32 nodes, 16 nodes, 8 nodes, and 4 nodes)
2. 3 options for the learning rate: 0.1, 0.001, 0.00001
3. 2 options for the number of words to represent the documents: 10,000 and 1,000

Only the training data (25,000 reviews) should be used for the 4-fold validation experiment.
- For each fold (of each option), display the plot of the training and validation accuracies and justify the selected model (i.e., at which epoch).
- Analyze the results of each option and select the top 3 choices (based on the accuracy averaged over the 4 folds).
- For each of the top 3 sets of options, generate predictions on the test data (this should be the first time you use the test data). Evaluate the performance of the 3 options, compare their ranking to that on the validation data, and comment on the results.

Use the newswires classification data and repeat the experiment outlined above. You need to design your own set of 12 options to consider and validate. Some of your options must illustrate overfitting, others must illustrate underfitting, and others should have a good generalization.
