# fashion-mnist

# Fashion-MNIST
For this project we are using the Fashion-MNIST dataset to predict the type of clothing. See https://github.com/zalandoresearch/fashion-mnist we will use the test set only once for each model, we will use cross validation for the tuning of the hyperparameters.

## Models
First we will use some traditional machine learning models that do not take the structure of the image into account and then we will look at convolutional neural networks. We have also defined some functions to help us evaluate our models. Our models will be objects that have a fit and a predict method, the first for training and the second for prediction.

## Logistic regression
We want to try different values for the C regularization so we use GridSearchCV.

## Naive Bayes
We use Gaussian Naive Bayes because of the continuous features.

## Random Forest

## Convolutional neural network
Convolutional neural networks are a specific type of neural networks that use the spatial structure of your data. They are used a lot in computer vision problem but also on text and time series. http://colah.github.io/posts/2014-07-Understanding-Convolutions/

## Convolutional model without dropout or pooling, 2 conv layers and 1 dense layers

## Convolutional model pooling, 3 conv layers and 2 dense layers, 0.1 dropout

## Convolutional model pooling, 5 conv layers and 2 dense layers, 0.1 dropout


