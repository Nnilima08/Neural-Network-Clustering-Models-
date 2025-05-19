In this report, we aim to optimize and extend an existing idea originally presented in the paper "Learning Deep Representations for Graph Clustering" by F. Tian, B. Gao, Q. Cui, E. Chen, and T. Liu. The original approach involves embedding a similarity graph using a deep autoencoder with a sparsity constraint, followed by applying the K-Means algorithm on the learned embeddings to produce clustering results.

While our model builds upon this foundational concept, it introduces several key differences. Specifically, we modify the construction of the graph similarity, redesign the loss function, and adopt a different training strategy for the model. We evaluate our approach against two prior methods, including the original 2014 work by Tian et al. and a later method proposed by S. Cao, W. Lu, and Q. Xu in 2016, using the same datasets for a fair comparison.

Below, we present a 2D visualization of the embeddings produced by our autoencoder model applied to the 3NG dataset, which consists of three selected categories from the 20 Newsgroups dataset.

![Uploading 2D_Embedded.png…]()
