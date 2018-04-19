# Atanasiu Stefan Demian - Data Analysis Portfolio
(under construction)

This repository is a collection of notebooks I wrote with the purpose of analyzing data and implementing machine learning algorithms. Some of the datasets used in the notebooks are from the book "Introduction to Statistical Learning" by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani, Springer, 2013 (abbreviated as ISLR henceforth). More information about the book can be found [here](http://www-bcf.usc.edu/~gareth/ISL/).

## Inference

### Deaths by horse kicks: Bortkiewicz's data
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/AtanasiuDemian.github.io/blob/master/Notebooks/RNit.nb.html)

This R Notebook is concerned with Ladislaus Bortkiewicz's investigation of the number of annual deaths by horse kicks in 14 different cavalry corps of the Prussian Army. This dataset is quite popular because it fits a Poisson distribution reasonably well.

## Regression

### Shrinkage Methods: Hitters dataset
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/Introduction-to-Statistical-Learning---Python/blob/master/Hitters.ipynb)

I apply Ridge and Lasso to the Hitters dataset from the ISLR package, containing data about Major League Baseball players. The results of the two models on the test set were compared with the performance of a multiple linear regression model using ordinary least squares. More information about the dataset can be found [here](https://rdrr.io/cran/ISLR/man/Hitters.html).

### Shrinkage and PCR: College dataset
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/Introduction-to-Statistical-Learning---Python/blob/master/College.ipynb)  

I analyze the College dataset from ISLR, which contains information about 777 universities and colleges in the US. The objective is to predict the number of applications received by a college using 4 regression models: Ordinary Least Squares, Ridge, Lasso and Principal Components Regression (PCR).

## Classification

### Leukemia Classification by Gene Expressions
[Notebook](https://nbviewer.jupyter.org/github/AtanasiuDemian/AtanasiuDemian.github.io/blob/master/Notebooks/Leukemia.ipynb)

The objective is to build a classification model from a high-dimensional dataset comprising gene expressions to predict two types of leukemia: acute myeloid leukemia (AML) and acute lymphoblastic leukemia (ALL), through logistic regression and dimensional reduction by PCA.

## Miscellaneous

### Kaggle Data Cleaning Challenge
[Notebook](https://www.kaggle.com/tanidemian/data-cleaning)

This was a 5 day programme tackling issues and techniques used for data cleaning. The notebook is organized as follows:  

Day 1 - Handling missing values  
Day 2 - Data scaling and normalization  
Day 3 - Cleaning and parsing dates  
Day 4 - Character encodings  
Day 5 - Fixing inconsistent data entry & spelling errors  
