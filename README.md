# Assignment_4

## K-fold Cross-validation (CV)

In this assignment we’ll be exploring cross-validation (CV). Specifically, K-fold cross-validation is a way to
estimate model prediction error. It utilizes the standard technique of splitting your dataset into a training
set (to fit your model) and a test set (to get test errors on new data that your model has not seen before).
However, it does this many (K) times, each time using a different test set. The idea is then that you can
actually use all of your data to train the model, and use K-fold CV to estimate the prediction error.
