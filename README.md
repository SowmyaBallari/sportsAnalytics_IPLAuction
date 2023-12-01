# sportsAnalytics_IPLAuction
Welcome to the IPL Player Auction Prediction System! This project aims to establish a relationship between IPL player statistics and the prices at which they are sold in auctions. By leveraging machine learning algorithms, specifically Linear Regression, Decision Tree Regression, Random Forest Regression, and AdaBoost Regression, we seek to predict player buying prices for IPL team franchises.

Development Tools
Language: Python
Notebooks: Jupyter Notebooks
Data/Problem Analytics
Data Sources
Player Performance Statistics Data (2016-2022):

Batsmen and bowler statistics from 2016 to 2022.
Key attributes include matches played, runs scored, highest score, wickets taken, etc.
Auction Data Set (2013-2022):

Information about players, the teams that bought them, the year of the auction, and the sold price.
Key attributes include player name, nationality, type (batsman, bowler, wicketkeeper), team name, and auction year.
Data Cleaning and Pre-processing
Joining Data Sets:

Combined player performance statistics and auction data using player names.
Addressed naming convention differences and averaged sold prices for players auctioned in multiple years.
Data Cleaning:

Removed redundant columns.
Eliminated duplicate observations.
Models Developed
Linear Regression:

Modeled the association between player statistics and auction prices.
Decision Tree Regression:

Utilized decision trees to predict auction prices based on player attributes.
Random Forest Regression:

Implemented an ensemble learning model for enhanced prediction accuracy.
AdaBoost Regression:

Combined multiple weak regression models to create a robust predictor.


Batsmen Model Evaluation
Model	MAE	MSE	RMSE
Linear Regression	17.94	600.22	24.50
Decision Tree	18.54	764.87	27.66
Random Forest	18.50	671.21	25.91
AdaBoost	18.80	557.95	23.62
Selected Model: Linear Regression

Bowler Model Evaluation
Model	MAE	MSE	RMSE
Linear Regression	15.13	287.98	16.97
Decision Tree	25.24	1436.68	37.90
Random Forest	11.42	177.66	13.33
AdaBoost	18.87	311.91	17.66
Selected Model: Random Forest Regression

Managerial Implications
Decision Support: The system assists IPL team franchise owners in making informed decisions on player purchases during auctions.

Budgeting: Enables budget planning for auction sessions, optimizing investments and ensuring higher profits.

Idea Sharing
Data Collection Challenges: Overcame data unavailability challenges by creating a comprehensive dataset.

Future Work:

Redesign the model for more accurate predictions by incorporating T20I and ODI formats.
Develop a model to integrate business auction purse with player investment for budget optimization.
Explore unsold player analysis for predicting better players out of unsold candidates.
