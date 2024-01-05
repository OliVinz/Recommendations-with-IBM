# Recommendations-with-IBM

# Recommendations with IBM
# Table of Contents
1.	Libraries 
2.	Project Motivation
3.	Data
4.	Project Outline
5.	Licensing, Authors, and Acknowledgements


# Libraries used:
1.	Numpy
2.	Pandas
3.	matplotlib
4.	nltk
# Project Motivation
This projects aim is to make recommendations of articles to users and new users and it involves rank based filtering, collaborative filtering, and SVD.
# Project Data
Provided by IBM. Can be found in the data folder.
# Project Outline
There are three components in this project.
1.	Exploratory Data Analysis
o	Getting to know the data and developing data understanding.
o	Distributions
o	The number of unique articles that have an interaction with a user.
o	The number of unique articles in the dataset (whether they have any interactions or not).
o	The number of unique users in the dataset. (excluding null values)
o	The number of user-article interactions in the dataset.
2.	Rank Based Recommendations
o	Find the most popular articles simply based on the most interactions.
o	In the absence of ratings for any of the articles, assume the articles with the most interactions are the most popular.
o	These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3.	User-User Based Collaborative Filtering
o	In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
4.	Matrix Factorization
o	Using the user-item interactions, build out a matrix decomposition. Using decomposition, evaluate performance.
# Licensing, Authors, and Acknowledgements
• Apache Licence	
• Udacity

