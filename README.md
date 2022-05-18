# Recursive-Partition-K-Means
The implementation of the paper ”An efficient approximation to the K-means clustering for massive data”
by Marco Capo, Aritz Perez, Jose A. Lozano. The goal of this paper was to develop an
improved K-Means (Recursive Partition K-Means) which would handle very large datasets. The
key element of this improvement is to partition the data and extract weights and representatives for
each partition. Then K-Means is performed on each representative in respect to the weights. The
goal is to minimize distance computations and error of the approximation. In this implementation
the RPKM algorithm will be reproduced and then compared with classic K-Means. The datasets used for this implementation, were artificial mixture of gaussians, or the real dataset: Gas sensor array under dynamic gas mixtures. The code was developed in kaggle were it is possible to find the dataset.
