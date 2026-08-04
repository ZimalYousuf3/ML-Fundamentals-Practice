# K-Means Clustering on Blob Data

Practicing unsupervised learning using K-Means clustering on artificially generated data. Covers finding the right number of clusters using the Elbow Method, training a K-Means model, and visualizing the resulting clusters along with their center points.

## What This Covers

- Generating synthetic clustered data using `make_blobs`
- Using the Elbow Method to determine the optimal number of clusters
- Training a K-Means model and assigning cluster labels to data points
- Visualizing clusters with a scatter plot, color coded by cluster
- Plotting cluster centers on top of the data to confirm grouping accuracy

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Scikit-learn (`KMeans`, `make_blobs`)

## Dataset

Synthetic dataset generated using `sklearn.datasets.make_blobs`, simulating customer `income` and `spending` values grouped into 4 natural clusters.
