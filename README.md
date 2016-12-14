# TI_DataMining

Data mining algorithms library in TI Basic for TI Calculators.

The list of implemented algorithms is as following:

## Classification

### K-nearest-neighbours

**Function:** knn(d_type, points[n,m], point[m])

**Description:** Algorithms returns the k-nearest neighbours of a specific point in the data set. The label of these points can then be used in order to classifiy the current point.

**State:** Implemented and tested.

### Decision Tree: ID3, C4.5 and CART

**Function:**

**Description:** Top down recursive divide and conquer approach used to construct a classification tree. The order of division of the tree by attribute is compited based on impurity measurements as the entropy gain (ID3), entropy gain and entropy split split (C4.5), Gini index (CART), 

**State:** TODO

### Naive Bayes Classifier

**Function:**

**Description:** Probabilistic classification based on Bayes Theorem and the assumption that all variables are conditionally independents.

**State:** Not planned.

### Bayesian Belief Network

**Function:**

**Description:** Probabilistic classification based on Bayes Theorem and on a network showing the variable dependency relations.

**State:** Not planned.

### Perceptron algorithm 

**Function:** neurontrain(point[m], weights[m+1], expected[m], learning rate)

**Description:** Algorithm used in order to train a Threshold Logical Unit and returning the list of weights. First elements of the weights input is the threshold value of the TLU.

**State:** Implemented and tested.

### Backpropagation algorithm

**Function:**

**Description:** Algorithm used in order to train a multi layer neural network. The algorithm computes the output of the first value in the data set, computes its error and backpropagate it from the last layer to the first ones.

**State:** TODO

### Support vectors machines

**Function:**

**Description:** 

**State:** TODO

## Clustering

### DBSCAN

**Function:** dbscan(d_type, points[n, m], epsilon, min_pts)

**Description:** Density based approach.

**State:** Implemented and tested.

### K-means

**Function:** kmeans_simp(d_type,centres[k,m],points[n,m],iterations) 

**Description:** Partional approach.

**State:** Implemented and tested.

### Partitioning Around Medoids (PAM)

**Function:** 

**Description:** Partional approach.

**State:** Started.

### Expectation Maximisation for Fuzzy set 

**Function:** fuzzy(d_type, centres[k,m], points[n, m], iteration)

**Description:** 

**State:** Implemented and tested.

### Expectation Maximisation for probabilistic model

**Function:** 

**Description:** 

**State:** TODO

### KL Transform

**Function:** kltransform(data[n,m]) 

**Description:** 

**State:** Implemented and tested.

## Outlier detection 

### Using 68, 95 and 99.7 intervals for normal distribution

**Function:** outiler_normal(points[n])

**Description:** Statistical approach based on the assumption that objects in the data set are generated from a normal distribution. From the maximum likelihood method, the values of mean and variance are computed. The 68%, 95% and 99.7% rules are then applied to each points of the data set to distinguish outliers.

**State:** Implemented and tested.

### Grub Test for normal distribution

**Function:** outlier_grub(point, points[n], alpha)

**Description:** Statistical approach based on the assumption that objects in the data set are generated from a normal distribution. The algorithm computes then the z-score of each points, a metric to compute its deviation from the data set. The z-score is then compared to the student distribution at a significance level of alpha / 2*n.

**State:** Implemented and tested. --TODO: Create as library not as program

### Detection of multivariate outliers with Mahalaobis distance

**Function:** 

**Description:** Adaptation of the grub test for outlier detection on multivariate elements by using the Mahalaonis distance.

**State:** Implemented. Should be tested.

### Detection of multivariate outliers with x²-statistic

**Function:** outlier_x2(points[n, m])

**Description:** Algorithm computing the x² distance of each points to other points in the data set and returning the ones with large values as outliers. 

**State:** Implemented and tested.

### Nestedloop algorithm

**Function:** nestedloop(d_type, points[n,m], distance_min, min_neighbours) 

**Description:** Algorithm using buffers in order to minimize the number of read made in the database.

**State:** Implemented and tested. (Not correct)

### Local Outlier Factor (LOF)

**Function:** lof(k, d_type, points[n,m]) 

**Description:** 

**State:** Implemented and tested.

### Angle-Based Oulier Factor (ABOF)

**Function:**

**Description:**

**State:** TODO
