### Question 1

Spectral Filters are...

- [x] A scalar function in "frequency-space" that diminish/amplify frequencies of a signal
- [ ] Dot products of eigenvectors that encode the amount of frequency found in a signal
- [ ] Derived from the eigen-decomposition of the Graph Laplacian
- [ ] The eigenvalues of the Graph Laplacian arranged in a diagonal matrix

### Question 2

The recipe for Spectral Convolution is...

- [ ] Inverse-FT -> Filter -> FT
- [ ] Filter -> FT -> Inverse-FT
- [x] FT -> Filter -> Inverse-FT
- [ ] Inverse-FT -> Filter -> FT

### Question 3

Check all that accurately describe the Graph Fourier Transform

- [ ] Is a continuous analog of the Discrete Fourier Transform defined on graphs
- [x] Is a projection of a signal on the eigen-basis of the Graph Laplacian
- [x] The frequency spectra is given by the eigenvalues of the Laplacian
- [ ] Is local because a single component only depends on values in a node's neighborhood
- [x] Is non-local because a single component depends on the signal of every node

### Question 4

Check all that accurately describe Wavelets

- [ ] Are another representation of the Fourier Transform
- [x] Are used to solve the non-locality problem of the Fourier Transform
- [x] Components are parameterized instances of a "mother wavelet" core, which can take many forms
- [ ] Have a single functional form
- [x] Require a continuous "scale" parameter

### Question 5

Check all that accurately describe Graph Wavelets

- [ ] Are localized in frequency only
- [x] Are localized in frequency and node proximity
- [ ] Define scale as a discrete parameter that represents neighborhood size
- [x] Define scale as a continuous multiplier of frequency

### Question 6

Spectral convolutions are localized by what mechanism?

- [ ] Only using low-frequency components of the Graph Laplacian
- [x] Approximating the wavelet transformation as a polynomial expansion of the Laplacian
- [ ] Re-scaling the Laplacian by its largest eigenvalue
- [ ] Applying our filters in the frequency domain