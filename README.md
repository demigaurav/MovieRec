**Movie Recommendation Project**

This project provides a movie recommendation system utilizing a MovieLens dataset of movies and user ratings. It leverages Python's pandas library for data manipulation and sklearn for machine learning algorithms.

**Data Overview**

The dataset contains two primary CSV files:

Movies.csv: Includes movieId, title, genres, and a filtered title with special characters removed.
Ratings.csv: Contains userId, movieId, rating, and timestamp data, enabling personalized recommendations based on user preferences.

**Functionality**

Text Processing: The **no_characs** function cleans movie titles by removing special characters.
TF-IDF Vectorization: Utilizes TfidfVectorizer to convert movie titles into a numerical format that can be analyzed for similarity.
Cosine Similarity: Implements cosine similarity to find top matching movies based on user input.
Interactive Widget: Integrates ipywidgets for a user-friendly interface allowing users to input a movie title and receive recommendations.

**Recommendation Algorithms**

Content-based Filtering: Recommends movies similar to the user's input based on title similarity using TF-IDF.
Collaborative Filtering: Identifies similar users and suggests movies based on ratings given by them, calculated via similarity scores between users’ preferences.

**Conclusion**

This movie recommendation system merges content-based and collaborative filtering techniques to provide personalized movie suggestions. The project demonstrates effective use of machine learning and data processing techniques in the context of entertainment and user experience enhancement.


For any further details on implementation or improvement suggestions, feel free to contribute!
