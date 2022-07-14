# Unsupervised Portfolio Classification

<hr>

## Read me, really!

In the folder ClusteringCrypto, two ipynb scripts provide unsupervised analysis for a set of crypotocurrency data. Both notebooks are identical, with the only difference being; the notebook with filename ending in 'sm' is adpated to work on Amazon's web services sagemaker.

<hr>

# ClusteringCrypto

## PCA

The script cleans up data from the crypto compare mini api, to perform both PCA and K-means clustering. The dataframe below is a sampling of the resulting analysis from a PCA analysis seeking 3 principal components:

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/pca.png)

## K-means

To determine how best to cluster these vectors using K-means, an elbow plot is obtained:

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/elbow.png)

The dataframe below presents a sample of the combined results from PCA and K-Means classification:

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/cluster.png)

## Visualiztions (Where it all makes sense!(mostly))

Graphs of Circulating Supply to Total Coins Mined, show how clusters are distributed; note the scales on each sample graph:

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/g1.png)

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/g2.png)

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/g3.png)

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/g4.png)

Finally the table below gives a sample of the list of tradable cyptocurrencies:

![](https://github.com/Femi-0/unit13-challenge/blob/main/ClusteringCrypto/Resources/table.png)
