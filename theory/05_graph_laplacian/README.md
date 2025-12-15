## Resources

- [Lecture video](https://youtu.be/1OLL7bwJRjY)
- [Slideshow pdf](https://drive.google.com/file/d/1RXtFA7Fd2dFc4075baZ8YNLLgvNfT5ek/view?usp=sharing)
- Code playing with the Graph Laplacian and its eigenvectors can be found in [this Jupyter notebook](./laplacian_eigenvectors.ipynb).

## Quiz

### Question 1

Check all that accurately describe the Laplacian

- [ ] It is a transformation of the adjacency matrix that encodes connectivity in the graph
- [ ] When operating on a node signal, gives the difference between a node and its neighbors
- [ ] It's eigenvalues are all <= 0
- [ ] The number of disconnected components in a graph equals the degeneracy of the 0-eigenvalue

### Question 2

The eigenvectors of the Laplacian with eigenvalue equal to 0 help find...

- [ ] High degree vs low degree nodes
- [ ] A partitioning of the nodes into disconnected components
- [ ] High centrality nodes
- [ ] Useful node embeddings

### Question 3

The Fiedler vector... (check all that apply)

- [ ] Is the eigenvector with the smallest eigenvalue
- [ ] Is the eigenvector with the smallest eigenvalue greater than 0
- [ ] Is the eigenvector with the largest eigenvalue
- [ ] Assigns a coordinate to each node that minimizes the distance between connected nodes
- [ ] Can partition the nodes into two clusters that minimizes the number of cross-cluster edges

### Question 4

Check all that accurately describe Laplacian Eigen-maps (LEMs)

- [ ] LEMs are coordinates given by the eigenvectors of the Laplacian
- [ ] LEMs are coordinates given by the eigenvalues of the Laplacian
- [ ] LEMs can be used as a dimensionality reduction technique
- [ ] "Spectral Clustering" is k-means clustering on LEMs
- [ ] Most information is contained in the high-frequency components

### Question 5

Check all that accurately describe the eigenvalues of the Laplacian

- [ ] Are all <= 0
- [ ] Are all >= 0
- [ ] Can be thought of as frequencies
- [ ] Are non-degenerate
- [ ] Are all real-valued

## Digging Deeper

- Bronstein, M. et al. “Geometric Deep Learning: Going beyond Euclidean data.” IEEE Signal Processing Magazine 34 (2017): 18-42. ([arXiv](https://arxiv.org/abs/1611.08097))
- 3Blue1Brown video on the Determinant ([YouTube](https://youtu.be/Ip3X9LOh2dk))
- 3Blue1Brown video on Eigenvectors and values ([YouTube](https://youtu.be/PFDu9oVAE-g))
- Benchmarking Graph Neural Networks ([arXiv](https://arxiv.org/abs/2003.00982)) - Makes the connection between Laplacian eigenvectors and Positional Encodings used in Transformer models