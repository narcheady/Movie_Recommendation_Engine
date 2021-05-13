# Movie Recommendation Engine using Netflix Dataset

In this modern world we are overloaded with data and this data provides us the useful information. But it is not possible for the user to extract the information which interest them from these data. To help the user to find out information about the product, recommendation systems were developed.</br>
Recommender system creates a similarity between the user and items and exploits the similarity between user/item to make recommendations.</br>
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what their recommendation engine can do on the same training data set. </br>(Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)</br></br>

## Data Description</br>
The movie rating files contain over 100 million ratings from 480 thousand randomly-chosen, anonymous Netflix customers over 17 thousand movie titles.  The data were collected between October 1998 and December 2005 and reflect the distribution of all ratings received during this period.  The ratings are on a scale from 1 to 5 (integral) stars. To protect customer privacy, each customer id has been replaced with a randomly-assigned id.  The date of each rating and the title and year of release for each movie id are also provided. Therefore, summarizing:</br>
MovieIDs range from 1 to 17770 sequentially. (Datatype - int)</br>
CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users. (Datatype - int)</br>
Ratings are on a five-star (integral) scale from 1 to 5. (Datatype - int)</br>
Dates have the format YYYY-MM-DD. (Datatype - datetime)</br></br>

## Steps Performed :</br>

### Data Collection and Data Pre-Processing 
	Dataset File Description 
	Movie File Description 
	Distribution of Ratings 
	Splitting the dataset into Train and Test (80:20) 
### Exploratory Data Analysis on Train Dataset 
	Number of ratings per month 
	Analysis on rating distribution 
	Analysis of movie ratings vs the day of the week 
### Computing Similarity matrix
	Creating USER-ITEM sparse matrix from data frame 
	PDF and CDF of Average Ratings of Users and Movies 
	Number of users in train data, Number of movies in train data 
	Movie-Movie similarity matrix 
### Featurizing data for regression problems 
	Featurizing Train Data 
	Featurizing Test Data 
### Transforming Data for Surprise Models
	Transforming Train Data 
	Transforming Test Data
### Applying Machine Learning Models
	Creating Utility Functions for Surprise models and XGBoost function
	1. XGBoost
	2. Matrix Factorization SVD
	3. Matrix Factorization SVDpp 
### Comparing all ML Models 
