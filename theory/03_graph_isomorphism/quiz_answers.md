### Question 1

If graphs G1 and G2 are isomorphic it means...

- [ ] G1 and G2 have the same number of nodes and edges, but different connectivity patterns
- [x] There's a mapping of nodes such that two nodes share an edge in G1 if and only if the corresponding nodes share an edge in G2
- [ ] G1 and G2 have the same low-level properties (e.g., degree), but may have different higher-order motifs (e.g., triangles and 6-cycles)

### Question 2

Which of these statements is true?

- [x] If two graphs are isomorphic, they will pass the 1-WL test
- [ ] If two graphs are not isomorphic, they will fail the 1-WL test

### Question 3

The number of possible permutations of a graph with N nodes and E edges scales as:

- [ ] N*E
- [ ] N^2
- [x] N!
- [ ] E^2

### Question 4

The 1-WL algorithm terminates when...

- [ ] the node colors/labels stop changing
- [x] the partition of nodes based on shared colors stops changing
- [ ] the multiset of neighbors stops changing
- [ ] the two graphs are isomorphic

### Question 5

Larger numbers of iterations of 1-WL...

- [ ] Result in "over-smoothing"
- [ ] Result in a partition that's less fine (i.e., larger partitions)
- [x] Includes information from more distant nodes and gives more fine partitioning (i.e. smaller partitions)

### Question 6

To assign a color to a node for a single iteration, the 1-WL algorithm considers... (Select all that apply)

- [x] The current node label
- [x] The multiset of neighbor labels
- [ ] The labels of the neighbor's neighbors
- [ ] The local closed triangles

### Question 7

Two graphs pass the 1-WL test if...

- [x] They have the same number of nodes in each partition when the algorithm converges
- [ ] They have the same node colors when the algorithm converges