# HackerEarth - Data Science Hiring Challenge

## Predict project's success

### Problem Statement
Kickstarter is a community of more than 10 million people comprising of creative, tech enthusiasts who help in bringing creative project to life. Till now, more than $3 billion dollars have been contributed by the members in fuelling creative projects. The projects can be literally anything – a device, a game, an app, a film etc.

Kickstarter works on all or nothing basis i.e if a project doesn’t meet it goal, the project owner gets nothing. For example: if a projects’s goal is $500. Even if it gets funded till $499, the project won’t be a success.

Recently, kickstarter released its public data repository to allow researchers and enthusiasts like us to help them solve a problem. Will a project get fully funded ?

In this challenge, you have to predict if a project will get successfully funded or not. 

#### This code scored Rank 4 on the private leaderboard

[Leaderboard](https://www.hackerearth.com/challenge/hiring/data-science-hiring-challenge/leaderboard/)

## <span style='color:Blue'>Approach and Feature Engineering:</span>

Projects were observed to have a clear trend with date and the most common words used in the name and the description of the project. Final submission is the xgboost model (bagged 8 times).

Types of features:
1. Date features
2. Text features

## <span style='color:Blue'>Tools used:</span>
1. python - 3.6.1
2. xgboost - 0.6
3. scipy - 0.19.0
4. sklearn - 0.18.1
5. pandas - 0.20.1
6. numpy - 1.12.1
