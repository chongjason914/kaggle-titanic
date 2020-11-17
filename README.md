# Titanic: Machine Learning from Disaster 

## Introduction
This repository contains an end-to-end analysis and solution to the [Kaggle Titanic survival prediction competition](https://www.kaggle.com/c/titanic/overview). I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
Given what we know about a passenger aboard the Titanic, can we predict whether or not this passenger has survived? In other words, we are training a machine learning model to learn the relationship between passenger features and their survival outcome and susbsequently make survival predictions on passenger data that our model has not been trained on.

This is a binary classfication problem in machine learning as we are classifying the outcomes of passengers as either survived or did not survive the Titanic.

## Evaluation metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our
model. This is known as accuracy.

## Data description

Below are the description of the features in the data:

- Survival: 0 = Did not survive, 1 = Survived

- Pclass: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.

- Sex: Male or female

- Age: Age in years, fractional if less than 1

- SibSp: Number of siblings or spouses aboard the titanic

- Parch: Number of parents or children aboard the titanic

- Ticket: Passenger ticket number

- Fare: Passenger fare

- Cabin: Cabin number

- Embarked: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

## Notebook content

**0. Introduction**

**1. Import libraries**

**2. Import and read data**

**3. Data description**

**4. Exploratory Data Analysis (EDA)**
- 4.1 Data types, missing data and summary statistics
- 4.2 Feature analysis
    - 4.2.1 Categorical variables
        - Sex
        - Pclass
        - Embarked
    - 4.2.2 Numerical variables
        - Detect and remove outliers using Tukey method
        - Numerical variables correlation with survival
        - SibSp
        - Parch
        - Age
        - Fare           

**5. Data Preprocessing**
- 5.1 Drop and fill missing values
- 5.2 Data transformation (log transformation)
- 5.3 Feature engineering
    - Title
    - IsAlone
    - Age*Class
- 5.4 Feature encoding

**6. Modelling**
- 6.1 Split training data
- 6.2 Fit data to model and make predictions
    - 6.2.1 Logistic regression
    - 6.2.2 Support vector machines
    - 6.2.3 K-nearest neighbours (kNN)
    - 6.2.4 Gaussian naive bayes
    - 6.2.5 Perceptron
    - 6.2.6 Linear SVC
    - 6.2.7 Stochastic gradient descent
    - 6.2.8 Decision tree
    - 6.2.9 Random forest
    - 6.2.10 CatBoost
- 6.3 Model evaluation and hyperparameter tuning
    - 6.3.1 Training accuracy
    - 6.3.2 K-fold cross validation
    - 6.3.3 Hyperparameter tuning for SVM

**7. Preparing data for submission**

**8. Possible extensions to improve model accuracy**

**9. Conclusion**

## References
I have made references to the following notebooks in the making of this notebook:
- [Titanic Data Science Solutions](https://www.kaggle.com/startupsci/titanic-data-science-solutions) by [Manav Sehgal](https://www.kaggle.com/startupsci)
- [Titanic Top 4% With Emsemble Modelling](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling) by [Yassin Ghouzam](https://www.kaggle.com/yassineghouzam)

## My platforms
Reach out to me if you have any questions! 
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/channel/UCQXiCnjatxiAKgWjoUlM-Xg?view_as=subscriber)
- [Medium](https://www.medium.com/@chongjason)
