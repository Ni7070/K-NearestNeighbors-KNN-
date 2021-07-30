# K-NearestNeighbors-KNN-

K-Nearest Neighbour is a Supervised Machine Learning
technique. It is one of the simplest machine learning algorithm
too.The KNN algorithm assumes that similar things exist near
from each other. In other way we can predict that, data points
that are close to each other may belongs to the same classes.
So, when a new point comes, its distances from all the other
points are calculated using: <br>
distance = $(x2 − x1)^2 + (y2 − y1)^2$ <br>
We were given some data that includes train data
and test data. We measured the distance of the test data from
the train data. Then, We took input from the user on how many
nearest neighbour they want. Then we sorted them by their
distances and took top k data with the lowest distances. As k
was an odd number, we could easily predicted the class of the
test data from the results of the majority class of the nearest
neighbour’s.
