# Starbucks Capstone Challenge



## Project Overview

This project is the capestone for the data scientist nandegree from Udacity.  I choose to work on a data set that contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). 

## Problem to solve 

Ideally, I would like to know from the data which people are more likely to respond to offers. Maximum level of engagement is that people received the offer, viewed it and completed it. This will help to know who to target with what type of offer in Starbucks marketing efforts which subsequently improve sales. The expected solution is a model that predict the customer response to an offer. Responding to offer will be defined as either viewing or completing the offer. If the customer received the offer but did not view it or complete it, this will be considered as not responding

## Python Libraries used 

 - `pandas` for data munipulation 
 - `numpy` for numbers crunching 
 - `math` for simple math operations
 - `json` for reading json files. 
 - `matplotlib.pyplot` and `seaborn` for data visualization
 - `sklearn` for machine learning algorithms 

 ## Results 

 The highest accuracy of our prediction across all the three models is 73% and the highest f1-score is 79%. I believe those metrics are good performance measurements because the data is balanced in terms of success and failure to responsd to offers. I have chosen those three models because they are robust and flexible and protect us from over-fitting the data. 

 