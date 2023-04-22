# CBOW and Skip-Gram Word Embeddings Notebook

This is a notebook where I implement word embeddings for both Arabic and English languages using the CBOW (Continuous Bag-of-Words) and Skip-Gram algorithms. Word embeddings are a powerful technique for representing words as vectors in a high-dimensional space, which can be used to capture semantic relationships between words.

In this notebook, I explore how the CBOW and Skip-Gram algorithms can be used to generate word embeddings for both Arabic and English languages. I demonstrate how to preprocess text data, train the word embedding models, and visualize the resulting embeddings using t-SNE (t-Distributed Stochastic Neighbor Embedding) technique.

Here's a sample visualization of the word embeddings generated from the Skip-Gram algorithm on the English corpus:

![image](https://user-images.githubusercontent.com/96589883/233775691-ee3fdb38-02f5-4f08-be01-f609d3a6210e.png)
Fig.1. Visualization of the word embeddings generated from the Skip-Gram algorithm on the English corpus showing how the word "bigger" and "grown" are close to each other, implying the similarity between them.

![image](https://user-images.githubusercontent.com/96589883/233775702-6c6ea8bb-1c22-40e0-b5f0-1d026596b0ad.png)
Fig.2. Visualization of the word embeddings generated from the Skip-Gram algorithm on the English corpus showing how the word "grown" is close to the word "bigger" (shown in Fig.1.), indicating their similarity.
