# Games-Recommender
Recommends Online Tournaments along with Entry fees to the users who play on the platform

This recommender system is based on the implicit feedback of the users since we do not have any explicit ratings provided by the user for the games they play.

The number of games played by each user in each game format is taken as the implicit feedback of the user.

ALS method of pyspark ml library has been used to train the recommendation model 

RMSE has been chosen as the evaluation metric
