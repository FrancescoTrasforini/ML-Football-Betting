An application of Machine Learning to football betting

The idea behind the development of those models is that the objective of betting companies and the objective of bettors are misaligned. 

The assumption is that betting companies are interested in predicting (and reacting to) the public's opinion on the outcome of football matches. In other words, betting companies are not trying to predict the outcomes themselves, but the optimal odds to allow them to maximize their profits. 
Thus, there may be opportunities to profit from "mispriced" betting odds. 

The models developed are svm classifiers trained on different amounts of data and an svm regressor. The regressor aims to find the "true" betting odds with the goal to find value bets.

The models identifies betting opportunities that are then given in input to a script, which uses the Kelly Criterion to simulate the possible profits to be had.
