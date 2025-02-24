# Trade-Prediction-Model-UCSB-DataOrbit-2025

Group: Max Rong, Daniel Larson, Justin Zhang, Albert Chui

What inspired: Our group was inspired by a mutual appreciation for soccer which led us to seek out and examine the relationship between player statistics and their probability of being traded.

How We Built: We preprocessed the data and the added new features within the dataset. Using xgboost we used GridSearchCv with scaled position weights to account for imbalanced t/f values within the set using the weighted values we then trained the model to predict the trade probability.

Challenges: The challenges we faced included a lack of time to create new features, which in theory if created would drastically improve the model accuracy

What we learned: We learned how clean and process datasets and then create new variables based on previously given variables. Using this processed dataset we improved on our data visualization skills while also starting our journey into machine learning modeling using the xgboost model.

Future Directions:
Improper data-processing led to decreased model performance, future directions:
-Understand positional information via hybrid k-means clustering & positional classification to give role specific ratings. Can also lead to better performance by allowing us to see if a team has too many players in a role, upping trade chance. Can also compare to best player in their role.
-Better time series features, such as rating change over time, team winrate over time, cumulative team winrate/season would lead to a better picture of a player's impact
-Can calculate player impact more accurately as a function of team winrate increase after they were traded, or while they were on it.
-Can view player's rating in comparison to average team rating/average role rating in the league/in their team
-Age - sports tends to be ageist.
-to name a few

A model ensemble could improve predictive capability as well, like using a RandomForest model for non-linear learning and anti-overfit. 
