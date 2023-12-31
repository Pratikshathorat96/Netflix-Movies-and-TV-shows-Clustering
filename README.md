![image](https://github.com/Pratikshathorat96/Netflix-Movies-and-TV-shows-Clustering/assets/120496034/30e73921-a033-43d4-999b-15d682a568dc)


# NETFLIX MOVIES AND TV SHOWS CLUSTERING
Netflix Movies &amp; TV shows Clustering - ML Unsupervised Learning The objective of this project is to analyze and cluster a dataset related to Netflix. 

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. 
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings. 

# In this project, you are required to do 

* Exploratory Data Analysis. 
* Understanding what type content is available in different countries 
* If Netflix has been increasingly focusing on TV rather than movies in recent years. 
* Clustering similar content by matching text-based features.
  
# Attribute Information

1. show_id : Unique ID for every Movie / Tv Show

2. type : Identifier - A Movie or TV Show

3. title : Title of the Movie / Tv Show

4. director : Director of the Movie

5. cast : Actors involved in the movie / show

6. country : Country where the movie / show was produced

7. date_added : Date it was added on Netflix

8. release_year : Actual Releaseyear of the movie / show

9. rating : TV Rating of the movie / show

10. duration : Total Duration - in minutes or number of seasons

11. listed_in : Genere

12. description: The Summary description

# Conclusion 

* It is interesting to note that the majority of the content available on Netflix consists of movies. However, in recent years, the platform has been focusing more on TV shows.

* Most of these shows are released either at the end or the beginning of the year.

* The United States and India are among the top five countries that produce all of the available content on the platform. Additionally, out of the top ten actors with the maximum content, six of them are from India.

* When it comes to content ratings, TV-MA tops the charts, indicating that mature content is more popular on Netflix.

* The value of k=15 was found to be optimal for clustering the data, and it was used to group the content into ten distinct clusters.

* Using this data, a Content based recommender system was created using cosine similarity, which provided recommendations for Movies and TV shows.
