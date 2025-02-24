# hyperparameter-optimization
Using K-Fold cross validation to optimize hyperparameters

Using the movie reviews classification data (imdb_data), used 4-fold cross validation to identify the best hyper-parameters. Considered the following configurations:

1. 3 options for the number of hidden layers:
  a. 1 layer (1 node)
  b. 2 layers (16 nodes, 4 nodes)
  c. 4 layers (32 nodes, 16 nodes, 8 nodes, and 4 nodes)
2. 3 options for the learning rate: 0.1, 0.001, 0.00001
3. 2 options for the number of words to represent the documents: 10,000 and 1,000

Only the training data (25,000 reviews) was used for the 4-fold validation experiment.
- The plot of the training and validation accuracies is displayed for each fold (of each configuration).
- The top 3 configurations (based on the accuracy averaged over the 4 folds) were selected. 
- For each of the top 3 configurations, predictions are generated on the test data. The performance of the 3 configurations were evaluated and compared to their ranking on the validation data. 

The experiment outlined above was repeated on the newswires classification data using a different set of 12 options to consider and validate. Some of the configurations illustrated overfitting, others underfitting, and others illustrated a good generalization.

The dataset files were too large to upload to the repository (Exceeded GitHub's 100 MB limit). I provided links to them below.

imbd_data
https://drive.google.com/drive/folders/1VEjdddS-AHYJ6NzvrhgQnXsu1RrBYYWc?usp=sharing

news_wire_data
https://drive.google.com/drive/folders/1NF_VlL4SHtJuVupWeHf5w7KFGLI7nJNw?usp=sharing
