# Link to Google Drive:
https://drive.google.com/drive/folders/187vPY-BSoRPTeVqylE-6391nDBc8MAa_?usp=share_link

*Note: Google Drive currently for viewing and is not set up for running. You can only see the results of the previously ran code. Also note that names of teammates have currently been redacted for privacy reasons.* 

# Project Description & Goal:
This project is a simulation of creating a predictive model for a bookmaking company specializing in football (soccer). The overall goal is to create a binary classification model that predicts whether a match will have >=3 or <=2 total goals (Above or below 2.5) - Though this may seem random, this is one of the most common football bets placed. Part of the simulation is to also demonstrate how having more or less data can influence the predictive power. Two models were created, one on an old dataset with only a few features, and one on another data set with dozens of features. Using the new, more expensive data, predictive power could be increased, and with increased accuracy, came an increase in expected profits (mathematical model in Google Drive under 'ProjectDescription.pdf'). 

# Results:
Average profit increase of 11% with the newly available data. Average overall increase in accuracy of 3% using XGBoost. 

# Descriptions of Python Notebooks:
1_Data_Exploration: This notebooks shows all of the data exploration/analysis performed before any data preprocessing took place.
2_Data_Preprocessing: About 98% of all data preprocessing was done here. It shows the full thought process of what was performed on the data and why it was performed.
3_baseline_m+xgboost+optimization: Here the baseline model which was evaluated, optimized, then evaluated again. 
4_NewAlternativeModel: New model with the extra data. Some extra data exploration and preprocessing, followed by evaluation and optimization of a few models. This is part one of two notebooks for this model’s tuning and evaluation. 
5_NewAlternativeModel_XGBoost: Here we tried to use XGBoost on the new model and ended up getting slightly better accuracy than on the previous models. This is where our final model is. 
6_Mathematical_model - Optimal Profit Increase: This final notebook is where the mathematical model is shown for outputting the profits from the newly bought data.


