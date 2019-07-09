# Recommendation-Systems-IBM-Articles
In this project, I explored four recommendation systems to on real data from the IBM Watson Studio platform:

1- Rank Based Recommendation.
2- User-User Based Collaborative Filtering.
3- Content Based Recommendations.
4- Matrix Factorization. 

# Packges
- pandas
- numpy
- matplotlib
- pickle
- seaborn
- scipy
- nltk

# Analysis Workflow

## Exploratory Data Analysis
Before making recommendations of any kind, I exploreed the data to identify any gaps, missing values and data distribution. I cleaned and prepared the data for ML analysis.

## Rank Based Recommendations
To get started in building recommendations, I first indentifies the most popular articles simply based on users interaction. Since there are no ratings for any of the articles, it make sense to assume that articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

## User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I took a look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

## Content Based Recommendations
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. I utilized NLP to develop a content based recommendation system. This recommender goes through each article title and finds the most common words(related to a content) throughout all the available articles. The recommender will recommend articles based on the sums of matched words in the title of an article and popularity.

## Matrix Factorization
Matrix decomposition is used to predict new articles an individual might interact with.