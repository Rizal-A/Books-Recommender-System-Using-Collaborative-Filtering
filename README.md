# Books-Recommender-System-Using-Collaborative-Filtering

![book-recommendations](https://github.com/Rizal-A/Books-Recommender-System-Using-Collaborative-Filtering/blob/main/assets/Book%20Recommendation.png)

This repository is about creating a book recommendation system with collaborative filtering using clustering nearest neighbors.

Dataset : [Kaggle Book Dataset](https://www.kaggle.com/datasets/saurabhbagchi/books-dataset)

Tools : Jupyter Notebook and Visual Studio

For Book Recommendations With Collaborative Filtering can be seen here : [Streamlit Link](https://books-recommender-system-using-collaborative-filtering07.streamlit.app/)

# Collaborative Based :

A collaborative filtering system is a method used to predict the usability of items based on previous user ratings. Clusters of users with same ratings or similar interests.

Book recommendation using cluster mechanism and parameters used are ratings or reviews

In short, collaborative filtering systems are based on the assumption that if a user likes item A and another user likes the same item A as well as another item, i.e. item B, then the first user may also be interested in the second item.

Issues are :

- User-Item using n X n matrix, so the computation cost is expensive
- Only the most popular will be chosen
- New items may not be recommended at all.
