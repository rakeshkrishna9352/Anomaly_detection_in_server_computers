# Anomaly_detection_in_server_computers

## Motivation
During my employement at TATA motors limited, there were many equiments used for manufacturing. These machines would sometimes function abnormally and only when something breaks down they could be detected. In such a case, an unsupervised Machine Learning model that detects anomaly before breakdown would be helpful.

## Overview
A unsupervised Machine Learning Model to detect anomaly in computer servers is developed using Multivariate Gaussian Distribution.

## Libraries Used
*NumPy, Pandas, Matplotlib, Seaborn, Scikit_learn (for metrics only)*

## Methodology
1. Verifying weather the features are normally distributed. Use log function in case any parameter is not normally ditributed
2. Estimating the parameters for computing probablity density
3. Creating a function to estimate Multivariate Gaussian Probablity density for given data.
4. Choosing the optimal threshold that maximises the F1 score on cross validation set.

## Model Report
The model achieved a F1 score of 74.0% and accuracy of 95% with 78.0% precision and 70.0% recall. Parameter focused.
