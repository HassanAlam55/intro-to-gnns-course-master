### Question 1

Which best describes Graph Convolutional Networks?

- [ ] A filter applied to the Fourier Transform of the signal
- [x] A linear approximation of localized spectral filters on graphs
- [ ] A scalar product between a parameter vector and the neighborhood patch with a pooling operator
- [ ] A full wavelet transformation where the wavelet is parameterized by the frequency

### Question 2

What is the primary purpose of truncating the polynomial expansion to the first power of L?

- [ ] It reduces the computational burden of using higher-order terms
- [ ] It allows multi-hop neighborhood information
- [x] It localizes the operation to the 1-hop neighborhood
- [ ] It requires fewer parameters to learn and reduces the problem of over-fitting

### Question 3

The spectral convolution operation is approximated by...

- [x] Chebyshev polynomials of the Laplacian
- [ ] The eigenvectors of the Laplacian
- [ ] The Fourier Transform of the node signal
- [ ] Hermitian wavelets

### Question 4

Check all that describe assumptions made to obtain the final form of GCN

- [x] The convolution operation can be approximated by the constant and first-order term of the Laplacian
- [x] The two polynomial expansion terms share parameters (but opposite signs), rather than having independent ones
- [ ] Frequencies are truncated using a threshold on the eigenvalues
- [x] Self-loops are added to the adjacency matrix to absorb the constant term

### Question 5

Check all that describe key benefits of GCN

- [x] GCN avoids the need to calculate the eigen-decomposition of the Laplacian
- [ ] GCN solves the over-smoothing problem by only allowing a single message-passing layer
- [x] GCN solves the non-locality issue of spectral filters by approximating the operation with a term linear in the Laplacian
- [x] GCNs make assumptions that allow a simplified layer form and show these assumptions do not harm or improve performance
- [ ] GCNs derive benefit from allowing higher-order terms in the polynomial expansion in L, which include multi-hop information