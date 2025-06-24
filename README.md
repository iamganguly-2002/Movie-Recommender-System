# Movie-Recommender-System

Recommendation system is an algorithm that suggests items users may like based on their preferences, behaviors, and interactions. There are three main types:

Content-Based Filtering: Recommends items similar to those a user has liked before, based on item features (e.g., genre, actors).

Collaborative Filtering: Suggests items based on user similarity, recommending items liked by similar users.

Hybrid Systems: Combine content-based and collaborative filtering for more accurate recommendations.

These systems are used in various platforms like e-commerce, streaming services, and social media to personalize user experiences and increase engagement.
Here the recommendation system is build for movies and It is of Hybrid type(both content and collaborative filtering is used).

# Data set 
Here is the dataset link - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

# Methodology

Both Content Based filtering and Collaborative filtering is used. short description of them is given below:

# Content Based filtering:

Content-Based Filtering is a recommendation approach that suggests items to users based on the features of the items and the user's past preferences. It operates under the principle that if a user liked an item, they will also like similar items that share comparable characteristics.
Mathematical Formula: Given:

A user 
(
u
)
An item 
(
i
)
Features of items represented as vectors in a feature space
The similarity between user preferences 
(
P
u
)
 (a vector of features representing the user’s interests) and item features 
(
F
i
)
 (a vector of features representing the item) can be calculated using the cosine similarity formula:

[
Similarity
(
u
,
i
)
=
P
u
⋅
F
i
|
P
u
|
|
F
i
|
]

Where:

(
P
u
⋅
F
i
)
 is the dot product of the user profile and item feature vectors.
(
|
P
u
|
)
a
n
d
(
|
F
i
|
)
 are the magnitudes (or norms) of the user and item vectors, respectively.
The system recommends items with the highest similarity scores to the user based on their profile.


