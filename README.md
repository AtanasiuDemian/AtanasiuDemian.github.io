# Atanasiu Stefan Demian - Data Analysis Portfolio
(under progress)

This repository is a collection of notebooks I wrote with the purpose of analyzing data and implementing machine learning algorithms. Some of the datasets used in the notebooks are from the book "Introduction to Statistical Learning" by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani, Springer, 2013 (abbreviated as ISLR henceforth). More information about the book can be found [here](http://www-bcf.usc.edu/~gareth/ISL/).

## Regression

### Shrinkage Methods: Hitters dataset
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/Introduction-to-Statistical-Learning---Python/blob/master/Hitters.ipynb)

I apply Ridge and Lasso to the Hitters dataset from the ISLR package, containing data about Major League Baseball players. The results of the two models on the test set were compared with the performance of a multiple linear regression model using ordinary least squares. More information about the dataset can be found [here](https://rdrr.io/cran/ISLR/man/Hitters.html).

### Shrinkage and PCR: College dataset
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/Introduction-to-Statistical-Learning---Python/blob/master/College.ipynb)

I analyze the College dataset from ISLR, which contains information about 777 universities and colleges in the US. The objective is to predict the number of applications received by a college using 4 regression models: Ordinary Least Squares, Ridge, Lasso and Principal Components Regression (PCR).

## Time Series 

### Predicting the Number of Airline Passengers
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/AtanasiuDemian.github.io/blob/master/Notebooks/AirPassengers.ipynb)

I analyze a time series dataset representing the monthly number (in thousands) of international airline passengers from January 1949 to December 1960. I look for an appropriate model by analyzing the ACF and PACF, and evaluating model performance using the AIC.
