


![movies_small](https://github.com/ranjeetha-virdi/Movie-Recommender/assets/81987445/f51acf3b-b2a0-4057-925f-13c47a0091c4)





## Movie Recommender:
This a movie recommender system developed by using Spark to recommend movies similar to the movie name and movie ID provided by a user.


## Recommendation Model:
A recommendation model, is an algorithm that aims to provide the most relevant and relatable information to a user depending on the behaviour of the user.

## Collaborative Filtering:

Collaborative filtering tackles the similarities between the users and items to perform recommendations. Meaning that the algorithm constantly finds the relationships between the users and their likes and in-turns does the recommendations based on similarities between the movies they like. The algorithm learns the similarities between the movies the users like. The most common technique is by performing cosinesimilarity function to find the similar movies that make up the interest of a particular set user of users based on their ratings. Once cosinesimilarity is calculated we will define a quality threshold to sort movies based on these scores.

## Data Collection:

Bulding a movie recommender system based on collaborative filtering, using MovieLens Dataset which were collected by the GroupLens Research Project
at the University of Minnesota details of which are available in the original publication accessible under:
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets:

History and Context. ACM Transactions on Interactive Intelligent
Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages.
DOI=http://dx.doi.org/10.1145/2827872
 
### Discription of Dataset: 
The dataset comprises of following:
    - 100,000 ratings (1-5) from 943 users on 1682 movies. 
	  - Each user has rated at least 20 movies. 
    - Simple demographic info for the users (age, gender, occupation, zip)


