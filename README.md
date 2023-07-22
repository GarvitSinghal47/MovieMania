# Content-Based-Movie-Recommender-System-with-sentiment-analysis

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.


The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.



## Similarity Score : 

   How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  

  ## Screenshots

1. Initial View
   
 ![1](https://github.com/GarvitSinghal47/MovieMania/assets/82756460/bbcbd2bd-3286-4397-a9e8-3979ecd09f09)

2. Search View

![2](https://github.com/GarvitSinghal47/MovieMania/assets/82756460/cc357ab5-f59c-4c40-88b7-0a8ba659ab66)


3. Movie Details View

![3](https://github.com/GarvitSinghal47/MovieMania/assets/82756460/f1bbb921-3bb6-4ef6-8506-e3ef8464ec5e)


4. User review View with sentiment analysis

![4](https://github.com/GarvitSinghal47/MovieMania/assets/82756460/c91bda8b-e94f-47d6-8946-811ca582e9eb)


5. Movie Recommendation View

![5](https://github.com/GarvitSinghal47/MovieMania/assets/82756460/9e357cdc-bd52-4a71-884c-9531bd34690d)




### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

