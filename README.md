# TI_DataMining

Data mining algorithms library in TI Basic for TI Calculators.

The list of implemented algorithms is as following:

## Classification

### K-nearest-neighbours

**Function:** knn(d_type, points[n,m], point[m])

**Description:** 

**State:** Implemented and tested.

### Perceptron algorithm 

**Function:** neuronupdate(point[m], weights[m+1], expected[m], learning rate)

**Description:** 

**State:** Implemented and tested.

### Backpropagation algorithm

**Function:**

**Description:** 

**State:** TODO

## Clustering

### DBSCAN

**Function:** dbscan(d_type, points[n, m], epsilon, min_pts)

**Description:**

**State:** Implemented and tested.

### K-means

**Function:** kmeans_simp(d_type,centres[k,m],points[n,m],iterations) 

**Description:**

**State:** Implemented and tested.

### Partitioning Around Medoids (PAM)

**Function:** 

**Description:**

**State:** Started.

### Fuzzy algorithm

**Function:** fuzzy(d_type, centres[k,m], points[n, m], iteration)

**Description:** 

**State:** Implemented and tested.

### KL Transform

**Function:** kltransform(data[n,m]) 

**Description:** 

**State:** Implemented and tested.

## Outlier detection 

### Using 68, 95 and 99.7 intervals for normal distribution

**Function:** outiler_normal(points[n])

**Description:**

**State:** Implemented and tested.

### Grub algorithl

**Function:** outlier_grub(point, points[n], alpha)

**Description:**

**State:** Implemented and tested.

### Nestedloop algorithm

**Function:** nestedloop(d_type, points[n,m], distance_min, min_neighbours) 

**Description:**  

**State:** Implemented and tested.

### Local Outlier Factor (LOF)

**Function:** lof(k, d_type, points[n,m]) 

**Description:**

**State:** Implemented and tested.

