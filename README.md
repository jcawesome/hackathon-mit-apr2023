# Hackathon: Shinkansen Travel Experience
## Introduction
In this notebook, I will try and use different techniques I have learned from the MIT - "Data Science and Machine Learning: Making Data-Driven Decisions" Program to complete my first Data Science and Machine Learning Hackathon.

## Business Case
**Context:** 
This problem statement is based on the Shinkansen Bullet Train in Japan, and passengers’ experience with that mode of travel. This machine-learning exercise aims to determine the relative importance of each parameter with regard to their contribution to the passengers’ overall travel experience. The dataset contains a random sample of individuals who travelled on this train. The on-time performance of the trains along with passenger information is published in a file named ‘Traveldata_train.csv’. These passengers were later asked to provide their feedback on various parameters related to the travel along with their overall experience. These collected details are made available in the survey report labelled ‘Surveydata_train.csv’.

In the survey, each passenger was explicitly asked whether they were satisfied with their overall travel experience or not, and that is captured in the data of the survey report under the variable labelled ‘Overall_Experience’.

The objective of this problem is to understand which parameters play an important role in swaying passenger feedback towards a positive scale. You are provided test data containing the travel data and the survey data of passengers. Both the test data and the train data are collected at the same time and belong to the same population.



**Problem:** The goal of the problem is to predict whether a passenger was satisfied or not considering his/her overall experience of traveling on the Shinkansen Bullet Train.

**Dataset**: 
The problem consists of 2 separate datasets: Travel data & Survey data. Travel data has information related to passengers and attributes related to the Shinkansen train, in which they traveled. The survey data is aggregated data of surveys indicating the post-service experience. You are expected to treat both these datasets as raw data and perform any necessary data cleaning/validation steps as required.

The data has been split into two groups and provided in the Dataset folder. The folder contains both train and test data separately.
* Train_Data
* Test_Data

> Target Variable: Overall_Experience (1 represents ‘satisfied’, and 0 represents ‘not satisfied’)


The notebook is divided into different sections:
* Data Dictionary
* Import Libraries
* Loading Dataset
* Overview of Dataset and Summary Statistics
* Exploratory Analysis
* Data Preparation for Modeling
* Building the Model:
	* Logistic Regression
	* Support Vector Machine(SVM)
	* Decision Tree
	* Random Forest	
* Summary

## Summary
In this hackathon, I won 2nd place with a highest accuracy of `0.9535981`.
![Performance Results](https://github.com/jcawesome/hackathon-mit-apr2023/blob/main/img/mit-hackathon-apr-2023-performance-results.png)

![Leaderboard Results](https://github.com/jcawesome/hackathon-mit-apr2023/blob/main/img/mit-hackathon-apr-2023-leaderboard-results.png)

## Future Improvements
To further improve on this notebook, I should do the following:
* Cleanup the notebook of unnecessary comments and add in proper description for each of the models used
* Combine both jupyter notebooks together (I had to separate to run parallel building of models)

To further improve on future hackathons:
* Develop a data pipeline for ETL and feature engineering
* Make use of GPU instead of running models in CPU (taking too loang to execute - hours rather than just possible minutes)
