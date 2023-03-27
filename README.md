# Model Building for Solubility Dataset
## Author: Pranjal Mishra

## Objective

To build a linear regression model to predict the solubility of small molecules in water based on their chemical descriptors.

## Dataset

The Delaney solubility dataset contains experimental solubility measurements for a diverse set of 1128 compounds, along with 4 molecular descriptors (LogP, MW, RB, and AP) calculated using the CDK software library.

## Libraries Used

* pandas
* scikit-learn
* matplotlib
* numpy
* pickle

## Steps
* Read in the data from the Delaney solubility dataset.
* Split the dataset into the feature matrix X (the 4 molecular descriptors) and the target variable Y (the experimental solubility measurements).
* Build a linear regression model using scikit-learn.
* Predict the solubility values using the model.
* Evaluate the performance of the model using mean squared error (MSE) and coefficient of determination (R^2).
* Visualize the relationship between experimental and predicted solubility values using a scatter plot with a trendline.
* Save the trained model as a pickle object for future use.
