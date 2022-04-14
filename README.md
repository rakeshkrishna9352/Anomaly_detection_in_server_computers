# Anomaly_detection_in_server_computers

## Overview
An unsupervised Machine Learning Model to detect anomalies in computer servers is developed using Multivariate Gaussian Distribution.

## Motivation
During my employment at TATA motors limited, there were machines and equiments used for manufacturing. These machines would sometimes function abnormally and only when something breaks down they could be detected. In such a case, an unsupervised Machine Learning model that detects anomalies before breakdown would be helpful.

## Libraries Used
*NumPy, Pandas, Matplotlib, Seaborn, Scikit_learn (for metrics only)*

## Methodology
1. Verifying whether the features are normally distributed. Use log function in case any parameter is not normally distributed.
2. Estimating the parameters for computing probablity density
3. Creating a function to estimate Multivariate Gaussian Probability density for given data.
4. Choosing the optimal threshold that maximises the F1 score on the cross-validation set.

## Model Report
The model achieved an F1 score of 74.0% and accuracy of 95% with 78.0% precision and 70.0% recall. More focus was given on increasing the recall value to minimise False Negatives.
