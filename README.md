****Cold Start Problems in Recommender Systems****
This project aims to tackle the cold start problem in recommender systems, focusing on movie recommendations. We evaluate standard techniques like collaborative filtering, matrix factorization, and content-based filtering, along with hybrid models, to address challenges with new users or items.

**Dataset**
Experiments are conducted on the MovieLens-small dataset, containing 100,000 ratings across 9,000 movies rated by 600 users.

**Methods**
1. Collaborative Filtering (CF)
Algorithm: Uses user-item interactions to recommend items based on similarities between users or items.
Experiment (User-based Collaborative Filtering): Recommends items based on the preferences of similar users.

2. Matrix Factorization
Algorithm: Decomposes the user-item interaction matrix into lower-dimensional matrices to discover latent features.
Experiment: Predicts ratings using singular value decomposition.

3. Content-Based Filtering
Algorithm: Recommends items based on the features and characteristics of movies that a user has liked in the past.
TF-IDF: Uses term frequency-inverse document frequency to assess the importance of words within a collection of documents.
BERT: Utilizes Bidirectional Encoder Representations from Transformers for a deeper understanding of language semantics.

4.Hybrid Recommender System-based Approach
Algorithm: Combines content-based filtering with matrix factorization or k-NN to improve recommendations.
Experiment (Simulating Cold Start): Simulates new user scenarios to evaluate the performance of different recommendation techniques

**Results**
Our experiments demonstrate the effectiveness of hybrid methods in reducing the loss per user compared to singular approaches, highlighting their potential in addressing the cold start problem.
