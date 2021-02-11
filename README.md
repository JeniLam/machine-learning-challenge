# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data,  machine learning models were created capable of classifying candidate exoplanets from the raw dataset.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)
- - -
## Process

* Preprocessed the raw data
* Scaled numerical data
* Separated the data into training and testing
* Used GridSearchCV to hypertune some models
* Tune and compare models/classifiers
- - -

## Report and Final Models Outcome

* Of the two models used the Random Forest out performed the Logistic Regression model prior to using the GridSearchCV hyper parameters.

* Using the GridSearchCV I was able to finetune the Logistic Regression a bit better than the original output

* Of the two models used the Random Forest would be the best method to use for futher research. 



### Logistic Regression:

|| Before GridSearchCV | After GridSearchCV
------------ | ------------- | -------------
Training Score | .66| .736
Test Score | .65| .717


### Random Forest Classifier:

|| Before GridSearchCV | After GridSearchCV
------------ | ------------- | -------------
Training Score | 1.0| .991
Test Score | .774| .769