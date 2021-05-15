" Use the command from y import x to import x from y.

Use train_test_split() to create training and test sets. Pass in the arguments X and y, and specify the keyword arguments test_size=0.4 and random_state=42.

In the param_grid dictionary, use l1_space as the grid of values to tune 'l1_ratio' over.

Use ElasticNet() to instantiate the regressor.

Inside GridSearchCV(), pass in the regressor elastic_net, parameter grid param_grid, and specify the number of folds to use. Then use the .fit() method on this with X_train and y_train passed in as arguments.

To compute r2, use the .score() method with X_test and y_test as arguments. To compute mse, use the mean_squared_error() function with y_test and y_pred as arguments. "
