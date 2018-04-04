---
title: Overview of Machine Learning Algorithms
author: Richard Wanjohi, Ph.D
date: '2018-04-02'
slug: overview-of-machine-learning-algorithms
categories:
  - Deep Learning
tags:
  - R
  - Python
  - Keras
  - Tensorflow
  - Theano
banner: ''
description: ''
images: []
menu: ''
---

<!--more-->


> Here we go!

***
# Problems:
* Classification problem: The target variable is qualitative (categorical/nominal)
   + Binary- Two possible outcomes only
      + e.g. Yes/No, 0/1
   + Multi-Class- More than 2 outcomes
      + e.g. Positive, Neutral, Negative  customer sentiment/feedback

* Regression problem: The target is quantitative (discrete or continuous) 
   + Can take any real number in Real line
      + e.g. Stock prices, estimated revenue, interest rates, price of house, Number of accidents 

   
### Others:
* Clustering
* Dimension reduction

***

Before we proceed here are some notations:

* M: Number of predictors/features/ independent variables
* N: Number of records/rows/observations/instances
* n: sample size 


## 1. Linear Regression:

* For continuous target variable
* Relationship between the  target and predictors variables is established by fitting a best line fit

```$$ y = b_{0} + b_{1}x_{1} + b_{2}x_{2}+ \cdots     b_{m}x_{m} $$```


* Pros:
    + Simple, easy to understand
    + Works most of the cases



```{r echo= False}
hist(iris[[2]])
```

```r
hist(iris[[2]])


```

```python
import pandas as pd

```

`$S_n = \sum_{i=1}^n X_i$`


## 2. Logistic Regression
This is a classification algorithm. It predicts the probability p of an event 
Odds = p/(1-p).  Log odds (logit) of p is modeled as linear combination of the predictors




## 3. Classification and Regression Trees (Decision Tree)



## 4. Naive Bayes




## 5. Ensembles

* Random Forest

* Boosted Trees
  + Adaptive boosting
  + Gradient Boosting
    * Gradient boost
    * XGBoost
    * Catboost
    
## 6. Support Vector Machine (SVM)



## 7. K-nearest neigbour (KNN)




