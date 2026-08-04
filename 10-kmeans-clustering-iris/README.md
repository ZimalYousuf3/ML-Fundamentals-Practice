# K-Means Clustering on Iris Dataset

Applying K-Means clustering on the classic Iris flower dataset to test whether unsupervised learning can find natural groupings that match the real flower species, without ever being told the species during training.

## What This Covers

- Performing a first look EDA on the dataset (info, describe, dtypes, missing values check)
- Scaling features using `StandardScaler`
- Using the Elbow Method to determine the optimal number of clusters
- Training a K-Means model and assigning cluster labels
- Visualizing clusters using petal length and petal width, along with cluster centers
- Comparing predicted clusters against the real species labels using `pd.crosstab`

## Result

K-Means with k=3 closely matched the real species groupings. Setosa was clustered with 100% purity, versicolor with 96% purity, and virginica with 72% purity, with some natural overlap between versicolor and virginica since these two species are visually similar in real life.

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Scikit-learn (`KMeans`, `StandardScaler`, `load_iris`)

## Dataset

Built-in `load_iris` dataset from `sklearn.datasets`, containing sepal and petal measurements for 3 iris species (setosa, versicolor, virginica).
