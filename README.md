# 565-final
In this project, we do the movie rating classification and recommendation. 
For classification, we use The IMDB Movie Dataset from Kaggle, which has 28 variables and 5043 observations. 
Before we apply the model to do the classification, we first do data cleaning work to evaluate whether some categorical variables are significant to the variable `imdb_score`, and we also dispose missing values so that the model can give better results. The goal for the classification part is not to find the exact score for each movie, the dataset has the variables `imdb_score` that is the exact rating on IMDB website. Instead, we just want to know how good or how bad a movie is. So we create 4 classes: “bad”, “fair”, “good”, and “excellent” according to the `imdb_score` of each movie. Then we used classification trees (unpruned and pruned), bagging, random forest, and KNN to classify all movies.

For recommendation, we implement two recommendation algorithms, content based and collaborative filtering. Then we assemble these two models to come up with our final recommendation system. For the first algorithm, we use the same dataset as we used before, while for the second algorithm, we add another dataset, The Movie dataset, which consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. It also includes tag genome data with 12 million relevance scores across 1,100 tags.

part1&2 folder contains code of classification problem and part3 folder contains recommendatioon algorithm.
