
### K-Means Clustering Algorithm w/ Principal Component Analysis (PCA) on Spotify Dataset

Spotify Developers API allows us to extract information about music tracks. What we are looking for is the audio features of a track.

The API returns 9 audio features for each track because of the huge dimensionality of the dataset we should reduce the columns of the dataset in order of 2 or 3 dimensions for better data visualization. In order to obtain a dataset of 3 dimensions we will use a dimensionality reduction technique called Principal Component Analysis or PCA.

We will use K-Means Clustering Algorithm to classify tracks into similar clusters. We will use an elbow chart to determine k, the number of clusters that the K-Means algorithm will use.

### Results
![3D Representation](https://github.com/josh-truong/spotify-kmeans/blob/main/demo.png)
![2D Representation](https://github.com/josh-truong/spotify-kmeans/blob/main/PCA%202D%20Clusters.png)

[Cluster 0 | ](https://open.spotify.com/playlist/3C6QUaAMJQwwkBPZSxYMR7)
[Cluster 1 | ](https://open.spotify.com/playlist/0lewEz46HxvvsrqrMqvxZ0)
[Cluster 2 | ](https://open.spotify.com/playlist/15XASDIJAv1biPeHVqMZ8y)
[Cluster 3 | ](https://open.spotify.com/playlist/5cSwYfTJmdHrJtDZGrt4PQ)
[Cluster 4 | ](https://open.spotify.com/playlist/5RjAESsCLVwY7qE2h0gQuE)
[Cluster 5 | ](https://open.spotify.com/playlist/70MkJHozNry5wQM9ah5hMu)
[Cluster 6 | ](https://open.spotify.com/playlist/2FTjPcYvq7k4HBhz61BKKt)
