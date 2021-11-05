### Movie Recomendation

The project involves recommending new videos for the user. It uses an <b>Alternating Least Square(ALS)</b> model for prediction.\
\
ALS is a matrix factorization algorithm and it runs itself in a parallel fashion. ALS is implemented in Apache Spark ML and built for a larges-scale collaborative filtering problems.
ALS is doing a pretty good job at solving scalability and sparseness of the Ratings data, and it’s simple and scales well to very large datasets.

