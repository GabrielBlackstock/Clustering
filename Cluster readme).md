# Temperature-Based Clustering Analysis for Car-Sharing Data

This repository contains a Python script that performs clustering on temperature data extracted from a car-sharing service dataset. The script utilises two popular clustering algorithms: KMeans and Agglomerative Clustering, to group the data into clusters based on temperature. The purpose is to uncover insights that could be pivotal for understanding usage patterns, forecasting demand, or optimising services based on temperature variations.

## Description

The Python script carries out the following steps:

1. **Data Importation:** Imports temperature data from a CSV file pertaining to a car-sharing service.
2. **Data Preparation:** Isolates temperature data for the clustering analysis.
3. **Standardisation:** Applies standardisation to the temperature data, ensuring a mean of 0 and a standard deviation of 1, which is essential for effective clustering.
4. **Clustering:** Performs clustering using two algorithms:
   - **KMeans:** A widely used clustering algorithm that partitions the data into k distinct clusters based on distance to the centroid of the clusters.
   - **Agglomerative Clustering:** A type of hierarchical clustering that builds nested clusters by merging or splitting them successively.

## Results

The terminal output presents the distribution of data points across the clusters for different values of k (number of clusters). Here's a summary of the clustering results:

### KMeans Clustering Distribution:

- **k=2:** Two clusters with 3241 and 5467 data points.
- **k=3:** Three clusters with distributions of 2666, 2409, and 3633 data points.
- **k=4:** Four clusters with distributions of 3216, 1384, 2409, and 1699 data points.
- **k=12:** Twelve clusters with varied distributions.

### Agglomerative Clustering Distribution:

- **k=2:** Two clusters with 5923 and 2785 data points.
- **k=3:** Three clusters with distributions of 2785, 2394, and 3529 data points. (Best result)
- **k=4:** Four clusters with distributions of 2394, 1972, 3529, and 813 data points.
- **k=12:** Twelve clusters with varied distributions.


