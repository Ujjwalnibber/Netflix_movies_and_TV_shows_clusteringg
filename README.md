**Problem Statement**

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting finding.

**Project Summary**


THE Netflix movies and TV shows clustering is a project where we shall draw insights from our data and will clusterr our dataset into relevant cluster. We shall start by first knowing our data but before that we need to import important libraries.Once done we shall now start by mounting our drive and then loading our dataset.

Once we have our dataset we shall go through shape and various columns to know what all our dataset contains* and what each column represent. We shall also go through description of column made available to us to know our dataset better.We have 7787 rows and 12 columns.

Now we shall move further to clean our dataset. To clean dataset we shall start by finding if there are any duplicate. But there are none so now we shall find if there are any null value.Since our dataset contains null set we shall drop some colum and for some column we shall subsitute the values. I shall look at various columns and their unique value count ,this helps me in knowing if vatibale is of categorical type ,how many categories are there. I can fimd data tupe of coulmn using info method. In this datset we have 12 coulmns and out of these 12 , 11 are of type object and one column of type int. To know more about this numerical column Ihave ised describe ethod that helps me to know maximum,minimum value count and mean and other parameters too

Now I shall be using graphs for visual representation and perform EDA using uni-variate,bi-varites..I shall finding be finding follwing information using graphs

Type of content
TOP 15 Netflix using countries
Count of content realeased per year
Different genre and their count
Different kind of rating and their count
Distribution of movies/shows according to months
Distribution according to date
Relationship between type of content and rating
TOP 10 countries and their preference of content type
Top 10 Genre of Movies
Top 10 genre of Shows
Top 15 actors on Netflix
Distribution of duration of movies
Most appeared words in title of Netflix content(WORDCLOUD)
Since cleaning is done EDA is done and we drawn conclusion about certain columns, it is time to pre process our data . I started by pre processing text by

removing punctuation
removing stopwords
stemming
tokenization
Once through with this process it is time to implement our model. I shall be creating two variables for storing length of text in description column and listed_in columnn and then rescaling it.Also we have done PCA(princpal compnent analysis)

Once done we shall impement our model and find out best value of k,I shall be using followinf methods

Elbow Method
Hierarchical Clustering
Agglomerative hierarchical Clustering
After this we shall conclude our project and write some insights
