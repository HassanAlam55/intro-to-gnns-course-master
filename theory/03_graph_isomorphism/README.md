## Resources

- [Lecture video](https://youtu.be/l-Q9AQZeq2E)
- [Slideshow pdf](https://drive.google.com/file/d/1J9s6QYveNQVBp_VXRrRUojmBwJYJPlw7/view?usp=sharing)

## Quiz

### Question 1

If graphs G1 and G2 are isomorphic it means...

- [ ] G1 and G2 have the same number of nodes and edges, but different connectivity patterns
- [ ] There's a mapping of nodes such that two nodes share an edge in G1 if and only if the corresponding nodes share an edge in G2
- [ ] G1 and G2 have the same low-level properties (e.g., degree), but may have different higher-order motifs (e.g., triangles and 6-cycles)

### Question 2

Which of these statements is true?

- [ ] If two graphs are isomorphic, they will pass the 1-WL test
- [ ] If two graphs are not isomorphic, they will fail the 1-WL test

### Question 3

The number of possible permutations of a graph with N nodes and E edges scales as:

- [ ] N*E
- [ ] N^2
- [ ] N!
- [ ] E^2

### Question 4

The 1-WL algorithm terminates when...

- [ ] the node colors/labels stop changing
- [ ] the partition of nodes based on shared colors stops changing
- [ ] the multiset of neighbors stops changing
- [ ] the two graphs are isomorphic

### Question 5

Larger numbers of iterations of 1-WL...

- [ ] Result in "over-smoothing"
- [ ] Result in a partition that's less fine (i.e., larger partitions)
- [ ] Includes information from more distant nodes and gives more fine partitioning (i.e. smaller partitions)

### Question 6

To assign a color to a node for a single iteration, the 1-WL algorithm considers... (Select all that apply)

- [ ] The current node label
- [ ] The multiset of neighbor labels
- [ ] The labels of the neighbor's neighbors
- [ ] The local closed triangles

### Question 7

Two graphs pass the 1-WL test if...

- [ ] They have the same number of nodes in each partition when the algorithm converges
- [ ] They have the same node colors when the algorithm converges

## Digging Deeper

* William Hamilton’s [Graph Representation Learning book](https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf) (Section 7.3)
* Clear formal exposition on [Graph Coloring](https://drops.dagstuhl.de/storage/00lipics/lipics-vol168-icalp2020/LIPIcs.ICALP.2020.73/LIPIcs.ICALP.2020.73.pdf)