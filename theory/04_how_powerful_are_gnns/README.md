## Resources

- [Lecture video](https://youtu.be/fDgMLidNLN8)
- [Slideshow pdf](https://drive.google.com/file/d/1ne32P2p_knZgzCO4_Gifvj-AYvwZXVXQ/view?usp=sharing)

## Quiz

### Question 1

What is the key similarity between GNNs and the 1-WL algorithm?

- [ ] They both use neural networks to approximate set functions
- [ ] They both use a node's neighborhood information to create a new representation on each iteration
- [ ] They both converge upon a stable graph partitioning
- [ ] They're both injective when mapping multi-sets

### Question 2

GNN's ability to distinguish a graph neighborhood is...

- [ ] As good or better than 1-WL
- [ ] Less than or equal to 1-WL
- [ ] Not firmly related to 1-WL

### Question 3

The primary bottleneck to limiting GNN's capacity for distinguishing non-isomorphic graphs compared to 1-WL is...

- [ ] The MESSAGE function
- [ ] The AGGREGATION function
- [ ] The UPDATE function

### Question 4

A function is "injective" if...

- [ ] It maps distinct inputs onto distinct outputs
- [ ] There's a one-to-many relationship between inputs and outputs
- [ ] There's a many-to-one relationship between inputs and outputs
- [ ] It can be inverted assuming no duplicates in the inputs

### Question 5

To generalize DeepSets method from a set-function approximator to a multiset-function approximator, we need to...

- [ ] Introduce a second Permutation Invariant network
- [ ] Collapse the multiset into a set by ignoring multiplicity
- [ ] Add a constant to the expression
- [ ] Restrict the aggregation function to SUM so that element multiplicity is preserved

### Question 6

The constant epsilon in the UPDATE equation of GIN... (check all that apply)

- [ ] Is designed to disambiguate whether an element is from the source node or its neighborhood
- [ ] Can be an irrational constant or learnable
- [ ] Has a meaningful impact on the empirical results in the paper
- [ ] Does NOT have a meaningful impact on the empirical results in the paper

### Question 7

1-layer perceptrons are not always sufficient for the UPDATE function because...

- [ ] Their linear-like behavior can break injectivity for multi-sets
- [ ] They generate vanishingly small gradients in practice
- [ ] They are not Permutation Invariant
- [ ] They make for a more difficult loss landscape and cause convergence issues

### Question 8

What is the appropriate sort order for expressive capacity of aggregation operators?

- [ ] MEAN > MAX > SUM
- [ ] SUM > MAX > MEAN
- [ ] SUM > MEAN > MAX
- [ ] MAX > MEAN > SUM

### Question 9

The difference in capability between MEAN and SUM is...

- [ ] MEAN captures structural information and SUM captures all information
- [ ] SUM maintains multi-set duplicity information and MEAN captures label distribution information
- [ ] MEAN and SUM have the same capabilities

### Question 10

The duplicity of elements in a multi-set are likely most important for what sort of GNN task?

- [ ] Node Classification
- [ ] Link Prediction
- [ ] Node Regression
- [ ] Graph Classification

## Digging Deeper

- Benchmarking Graph Neural Networks ([arXiv](https://arxiv.org/abs/2003.00982)):
  - Paper comparing regular GNNs to theoretically more expressive ones
  - Shows WL-GNNs do worse than GCN-based architectures on basic benchmarks
  - WL-GNNs are expensive in both space/time complexity and do not lend themselves to batching
- Breaking the Limits of Message Passing GNNs ([arXiv](https://arxiv.org/abs/2106.04319))
- Reconstruction for Powerful Graph Representations ([arXiv](https://arxiv.org/abs/2110.00577))
- On the Limitations of Representing Functions on Sets ([arXiv](https://arxiv.org/abs/1901.09006))