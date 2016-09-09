# Using-k-means-to-Detect-Network-Intrusion
KDD cup data of 1999 are used as input datahttps://www.dropbox.com/s/y9uq4n16jouj2jo/kddcup.data.gz?dl=0.
It contains about 5 million connec- tions. For each connection, the dataset tells us information like the number
of bytes sent, login attempts, TCP errors, and so on. Each connection is one line of CSV formatted data, containing 
about 40 different features.
In order for your test your code and ensure that things are running correctly, you will have to download the smaller
dataset (which is only 10% of the original dataset) and still has the same characteristics of the original dataset. 
This dataset is available here: https://www.dropbox.com/s/wywx3mdqdso2tq3/kddcup.data 10 percent.gz?dl=0.

k-means, a widely used clustering algorithm,aims to partition data into k clusters in which each datum belongs
to the cluster with the nearest distance to the center of the cluster. Also, k-means is used to detect anomalous 
network connection in the KDD cup data of 1999. The steps to cluster the data are shown as follows.
1.Parsing KDD cup data and first pass at clustering with k=2.
2.Choosing k for the parsed KDD cup data.
3.Normalizing the feature space.
4.Improving the clustering with labels.
5.Interpreting the clusters.
