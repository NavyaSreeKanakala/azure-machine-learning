# azure-machine-learning
The repository contains projects on three different analysis namely Regression, Classification & Cluster
# Regression on AirQuality data in Azure ML Studio
## Objective
The objective of the experiment is to predict Relative Humidity(RH) in air based on other contents in air at a given point of time.
## Description
Machine Learning has been pervading many fields & Meteorology is one of them. The data on multiple detrimental contents in air was captured by sensors set up in a polluted location of an Italian city. 
## Algorithms used
Linear Regression, Decision Forest Regression, Boosted Decision Tree & Neural Network
## Core Analysis
All the attributes were well studied before performing Data Wrangling in which we did some feature transformations & replacement of missing cells executing R Script , Python Script other Azure ML modules.The prepared data set was all the way used for Regression Analysis with powerful Azure ML algorithms. The test results with different algorithms were assembled in a meaningful format for end users to understand.

# Classification on Breast Cancer data in Azure ML Studio
## Objective
The goal of the experiment is to predict whether or not tumor is malignant
## Description
For this Healthcare Analytics the data on Breast Cancer was collected from an online source. The data was was understood from various aspects doing some visualization & other Statistical analysis.
## Algorithm used
Support Vector Machine
## Core Analysis
Data Wrangling was done through tabulation & visualization to prepare the data set for final analysis & finally applied SVM of Azure ML Studio & received desired outcome.

# Cluster Analysis on Violent Crime data in Azure ML Studio
## Objective
The purpose of the experiment is , assigning observations to groups or clusters based on the similarity they exhibit among themselves
## Description
The data set contains fifty instances of violent crime of different types across fifty states of the USA in 1973. The crime types are namely Murder,Assualt,Rape.Along with crime types Urban Population of each state of the USA is tabulated correspondingly.
## Algorithm used
K-Means
## Core Analysis
The data was studied well & found to have some missing cells. The missing cells were replaced with MICE(Multivariate Imputation by Chained Equations) method. After missing value replacement the attributes were visualized through scatter plots to derive some insights. The final step involved was building a clustering model with K-Means that helps to assign the instances to clusters chosen beforehand using proper method. The performance of the model was evaluated by observing the SSW(Sum of Squared Within) of each clusters. The entire experiment was conducted using both Azure modules & executing R Script.



