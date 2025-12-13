### Question 1

Check all that accurately describe the Laplacian

- [x] It is a transformation of the adjacency matrix that encodes connectivity in the graph
- [x] When operating on a node signal, gives the difference between a node and its neighbors
- [ ] It's eigenvalues are all <= 0
- [x] The number of disconnected components in a graph equals the degeneracy of the 0-eigenvalue

### Question 2

The eigenvectors of the Laplacian with eigenvalue equal to 0 help find...

- [ ] High degree vs low degree nodes
- [x] A partitioning of the nodes into disconnected components
- [ ] High centrality nodes
- [ ] Useful node embeddings

### Question 3

The Fiedler vector... (check all that apply)

- [ ] Is the eigenvector with the smallest eigenvalue
- [x] Is the eigenvector with the smallest eigenvalue greater than 0
- [ ] Is the eigenvector with the largest eigenvalue
- [x] Assigns a coordinate to each node that minimizes the distance between connected nodes
- [x] Can partition the nodes into two clusters that minimizes the number of cross-cluster edges

### Question 4

Check all that accurately describe Laplacian Eigen-maps (LEMs)

- [x] LEMs are coordinates given by the eigenvectors of the Laplacian
- [ ] LEMs are coordinates given by the eigenvalues of the Laplacian
- [x] LEMs can be used as a dimensionality reduction technique
- [x] "Spectral Clustering" is k-means clustering on LEMs
- [ ] Most information is contained in the high-frequency components

### Question 5

Check all that accurately describe the eigenvalues of the Laplacian

- [ ] Are all <= 0
- [x] Are all >= 0
- [x] Can be thought of as frequencies
- [ ] Are non-degenerate
- [x] Are all real-valued