# Driving-Style-Classifier-
Support vector machine model to classify driving style on horizontal curves as ‘Normal’ or ‘Aggressive’

# About

We have raw (for e.g. Data for 50 Drivers, Data point(including velocity,heading,GPS,sensor data etc.) in every 1/20th sec i.e 20Hz, Calibration of the fish-eye camera (for mappping camera world to real world))

The goal ultimately is to predict probable trajectory of vehicle by its current position at curve also taking into account heterogeneity at pathway corresponding to different types of road agent such as vehicle in same direction, vehicle in opposite direction,animal,pedestrian,speed breaker(will be noted by me manually at a curve I choose to analyse on and given different identifiers).
First initial days involved learning more about data and a week to learn software like Race logic and QGIS that aided in smooth working.
There are different approaches to the problem 
This involved reading about different statistical models and research paper in the vicinity of this topic.
Bayes' theorem, Kalman filters, Neural networks and about Hidden Markov Models (HMMs) and Markov Chain.
The model will use past trajectories as training data and continue to predicts spatial coordinates that further form the probable trajectory. 
I will then choose one of the curve for which I'll make my initial model, though a model for interaction with nearby road-agents needs to be considered Initially for simplicity I'll not consider the data where these agents were accounted for and only work on the left ones(50-x drivers)
Next part will be the data pre-processing, so that it can be used by our model 
Then I'll learn about the application part of the chosen model and apply it on our data at that particular curve.
So at the end of the month of December I hope to achieve prediction of probable future trajectory at one of the chosen curve (which can later be expanded for all of the curves) without taking road-agents into account.

