# Bulldozer Price Prediction System Using Machine Learning
<p align=center><img src="https://img.shields.io/badge/Last%20Commit-February 2021-brightgreen" hspace=20> <img src="https://img.shields.io/badge/Project%20Status-Open-brightgreen"></p>
<img src=https://storage.googleapis.com/kaggle-competitions/kaggle/3316/media/bulldozer.jpg>

Kaggle Link : https://www.kaggle.com/c/bluebook-for-bulldozers/overview

The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

Fast Iron is creating a "blue book for bull dozers," for customers to value what their heavy equipment fleet is worth at auction.

## Problem Definition

Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.

## Data

Dataset Link : https://www.kaggle.com/c/bluebook-for-bulldozers/data <br>
I am unable to include the dataset in this repository due to it's size. Please make sure to visit the link given above to download all the datasets necessary for this project. Make sure to store all the dataset in the folder 'data'.

## Table of contents :hourglass:

1. Environment setup :white_check_mark:
2. Gathering the data :white_check_mark:
3. Data Preprocessing and EDA 
   - Feature extraction :white_check_mark:
   - Converting Strings to Categories :white_check_mark:
   - Fill missing values :white_check_mark:
4. Model experimentation :hourglass:
   - Hyperparameter tuning tsing RandomizedSearchCV :white_check_mark:
   - Training the model with best parameters :white_check_mark:
5. Predictions on test dataset :white_check_mark:
6. Feature importance :white_check_mark:

## Results :hourglass:
Random Forest Regressor : RMSLE 0.24 (Top 100 leaderboard)
