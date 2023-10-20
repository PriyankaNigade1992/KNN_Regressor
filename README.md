# K-Nearest Neighbors (KNN) Regressor from Scratch

## Overview
This Python project provides an implementation of the K-Nearest Neighbors (KNN) regressor algorithm from scratch. It allows you to choose from different distance calculation methods, including Euclidean, Manhattan, and Minkowski, with a customizable 'p' value for the Minkowski distance.

## How to Use
1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/KNN_Regressor.git

# Make predictions on new data using a specific distance calculation method and 'p' value
predictions = knn.predict(X_test, method='euclidean')
