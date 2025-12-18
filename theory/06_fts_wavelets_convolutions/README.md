## Resources

- [Lecture video](https://youtu.be/ScmpdfBnfUE)
- [Slideshow pdf](https://drive.google.com/file/d/1TITdMnWEIObP6MRWx5SJ6ucpEf9FfiVm/view?usp=sharing)

## Quiz

### Question 1

Spectral Filters are...

- [ ] A scalar function in "frequency-space" that diminish/amplify frequencies of a signal
- [ ] Dot products of eigenvectors that encode the amount of frequency found in a signal
- [ ] Derived from the eigen-decomposition of the Graph Laplacian
- [ ] The eigenvalues of the Graph Laplacian arranged in a diagonal matrix

### Question 2

The recipe for Spectral Convolution is...

- [ ] Inverse-FT -> Filter -> FT
- [ ] Filter -> FT -> Inverse-FT
- [ ] FT -> Filter -> Inverse-FT
- [ ] Inverse-FT -> Filter -> FT

### Question 3

Check all that accurately describe the Graph Fourier Transform

- [ ] Is a continuous analog of the Discrete Fourier Transform defined on graphs
- [ ] Is a projection of a signal on the eigen-basis of the Graph Laplacian
- [ ] The frequency spectra is given by the eigenvalues of the Laplacian
- [ ] Is local because a single component only depends on values in a node's neighborhood
- [ ] Is non-local because a single component depends on the signal of every node

### Question 4

Check all that accurately describe Wavelets

- [ ] Are another representation of the Fourier Transform
- [ ] Are used to solve the non-locality problem of the Fourier Transform
- [ ] Components are parameterized instances of a "mother wavelet" core, which can take many forms
- [ ] Have a single functional form
- [ ] Require a continuous "scale" parameter

### Question 5

Check all that accurately describe Graph Wavelets

- [ ] Are localized in frequency only
- [ ] Are localized in frequency and node proximity
- [ ] Define scale as a discrete parameter that represents neighborhood size
- [ ] Define scale as a continuous multiplier of frequency

### Question 6

Spectral convolutions are localized by what mechanism?

- [ ] Only using low-frequency components of the Graph Laplacian
- [ ] Approximating the wavelet transformation as a polynomial expansion of the Laplacian
- [ ] Re-scaling the Laplacian by its largest eigenvalue
- [ ] Applying our filters in the frequency domain

## Digging Deeper

* Hammond, David K., Pierre Vandergheynst, and Rémi Gribonval. "Wavelets on graphs via spectral graph theory." Applied and Computational Harmonic Analysis 30.2 (2011): 129-150. ([arXiv](https://arxiv.org/abs/0912.3848))
* Ortega, A., Frossard, P., Kovačević, J., Moura, J. M., & Vandergheynst, P. (2018). Graph signal processing: Overview, challenges, and applications. Proceedings of the IEEE, 106(5), 808-828. ([arXiv](https://arxiv.org/abs/1712.00468))
* Bronstein, M. et al. “Geometric Deep Learning: Going beyond Euclidean data.” IEEE Signal Processing Magazine 34 (2017): 18-42. ([arXiv](https://arxiv.org/abs/1611.08097))