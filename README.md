
### K-Means Clustering Algorithm w/ Principal Component Analysis (PCA) on Spotify Dataset

Spotify Developers API allows us to extract information about music tracks. What we are looking for is the audio features of a track.

The API returns 9 audio features for each track because of the huge dimensionality of the dataset we should reduce the columns of the dataset in order of 2 or 3 dimensions for better data visualization. In order to obtain a dataset of 3 dimensions we will use a dimensionality reduction technique called Principal Component Analysis or PCA.

We will use K-Means Clustering Algorithm to classify tracks into similar clusters. We will use an elbow chart to determine k, the number of clusters that the K-Means algorithm will use.

