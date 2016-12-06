# Peer-graded-Assignment-Exercise-Prediction-Assignment
The goal of the project is to predict the manner in which participants did the exercise using Weight Lifting Exercise Data set.
Quantified Self devices are becoming more and more common, and are able to collect a large amount of data about people and their personal health activities. The focus of this project is to utilize some sample data on the quality of certain exercises to predict the manner in which they did the exercise.
This analysis is meant to be the basis for the course quiz and a prediction assignment writeup. The main goal of the project is to predict the manner in which 6 participants performed some exercise as described below. 
Three ML models, namely, Decision Tree, GBM and Randon Forest algorithms were considered among which Random forest was found to be most accurate, hence was applied to test the cases. 
The training data for this project are available at:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available at:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


The data for this project come from : http://groupware.les.inf.puc-rio.br/har. 
Random Forests gave an Accuracy in the myTesting dataset of 99.89%, which was more accurate that what I got from the Decision Trees or GBM. The expected out-of-sample error is 100-99.89 = 0.11%.
