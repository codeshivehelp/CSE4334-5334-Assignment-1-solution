# CSE4334-5334-Assignment-1-solution

Download Here: [CSE4334/5334 Assignment 1 solution](https://jarviscodinghub.com/assignment/cse4334-5334-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1
(k-means, 55pts) The dataset provided for this problem NBAstats.csv is stats from NBA players. The
players are indexed by their names, and they are labeled by 5 different positions: {center (C), power forward
(PF), small forward (SF), shooting guard (SG), point guard (PG)} and there are 27 attributes, e.g., age,
team, games, games started, minutes played and so on (that makes total of 29 columns in the data matrix).
Make sure that you standardize the data (zero-mean and standard deviation = 1) before you analyze the
data.
1. (30pts) Write a function cluster = mykmeans(X, k) that clusters data X ∈ R
n×p
(n number of
objects and p number of attributes) into k clusters.
2. (10pts) For this problem, use all features except team. Use your code to group the players into
k = {3, 5} clusters. Report the centers found for each clusters for each k, distribution of positions in
each cluster and your brief observation.
3. (5pts) Some of the attributes are perhaps redundant in terms of Linear Algebra. Report which ones
are redundant and explain why.
4. (10pts) For this problem, use the following set of attributes {2P%, 3P%, FT%, TRB, AST, STL,
BLK} to perform k-means clustering with k = {3, 5}. Report the centers found for each clusters for
each k, distribution of positions in each cluster and your brief observation.
Instructor: W. H. Kim (won.kim@uta.edu), TA: Priyank Arora (priyank.arora@mavs.uta.edu) Page 1 of 2
CSE4334/5334 Data Mining Assignment 1
Problem 2
(k-NN, 45pts) The dataset provided for this problem NBAstats.csv is stats from 475 NBA players. The
players are labeled by 5 different positions: {center (C), power forward (PF), small forward (SF), shooting
guard (SG), point guard (PG)} and there are 27 attributes, e.g., age, team, games, games started, minutes
played and so on. Use the first 375 players as training data and remaining 100 players as testing data. Make
sure that you standardize the data (zero-mean and standard deviation = 1) before you analyze the data.
1. (25pts) Write a function class = myknn(X, test, k) that performs k-nearest neighbor (k-NN) classification where X ∈ R
n×p
(n number of objects and p number of attributes) is training data, test is
testing data, and k is a user parameter.
2. (10pts) For this problem, use all features except team. Use your k-NN code to perform classification.
Set k = {1, 5, 10, 30} and report their accuracies and your observation.
3. (15pts) For this problem, use the following set of attributes {2P%, 3P%, FT%, TRB, AST, STL,
BLK} to perform k-NN classification with k = {1, 5, 10, 30}. Report accuracies for each k and your
observation.

