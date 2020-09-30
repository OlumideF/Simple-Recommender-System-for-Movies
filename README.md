# Simple-Recommender-System-for-Movies

# Objective:
To develop a simple algorithm that recommends movies in the MovieLens data by looking at the movies that are closest to it in terms of genre and popularity(rating).

# Concept:
Every movie in the data set has additional information on it. For instance, the genre it belongs to such as science fiction, comedy, drama, and action. Also, we shall look at the popularity of the movie, that is the number of people that rated it and the average rating of each movie. Therefore, we shall combine each movie genre and rating to create a metric of the distance between each film to implement the recommendation system.

# Scope:
It is important to note that fully developed and deployed recommendations systems are complex and resource-intensive. It requires heavy linear algebra background. Conversely, we shall create a readable and uncompounded version using 'item similarity' in this project.

# Methodology:
There are two most common types of recommender systems:
Content-Based - focus on the attributes of the items and give a recommendation based on the similarity between them.
Collaborative Filtering - gives a recommendation based on the knowledge of the users' attitude. The system recommends based on the wisdom of the crowd (In such cases, you would see something like 'people that viewed movie A also viewed movie B and C').
In real-world, Collaborative Filtering (CF) is commonly used than Content-Based Systems because it gives a better result, and it is relatively easy to understand provided you have linear algebra background.

Similarly, the CF algorithm can perform feature learning on its own that is it can determine what features to use when recommending items. In a broader view, CF is subdivided into Memory-based CF and Model-based CF. we shall consider Memory-based CF by computing cosine similarity in another publication. However, in this publication, we shall create a content-based recommender system for a data set of movies.

NOTE: The algorithms were compile in google colab to develop a simple recommender system for movies
