# NBAPlayers
In this project I decided tp try and predict an NBA players average pts per game for a selected season. 

I decided to use a neural network for the model. 

I had a dataset for every NBA player who played in the past 16 seaons. Most players appear multiple times, because they played multiple seasons. 

I focused on the age, player height, weight, and number of games played. 

Realizing that it was going to get an accurate reading, I decided to compress the data into clusters of data. Therefore the network would not be predicting, 
the exact pts, but what range of points a player would produce. 

I ended up clustering the ages and pts of players, that way the model would get a higher accuracy, without a great loss of precision. 

Ultimately the model ended with a 74% accuracy. 
