## Resources

- [Lecture video](https://youtu.be/foe5H9AG_4M)
- [Slideshow pdf](https://drive.google.com/file/d/1R7y4QMi7Vo5y_M-kGDvuvIJ_vNFrAX3k/view?usp=drive_link)

## Quiz

### Question 1

Which of these is NOT a standard function in the Neural Message Passing framework?
- [ ] Update
- [ ] Propagation
- [ ] Aggregation
- [ ] Message

### Question 2

The Message function can operate on which inputs? (Select all that apply)
- [ ] The source node features
- [ ] The destination node features
- [ ] The edge features
- [ ] The aggregate of neighborhood messages

### Question 3

If you shuffle the order of the messages, the Aggregation function returns...
- [ ] The same output
- [ ] Different output

### Question 4

The Update function can operate on which inputs? (Select all that apply)
- [ ] The source node features
- [ ] The destination node features
- [ ] The edge features
- [ ] The multiset of messages
- [ ] The aggregate of neighborhood messages

### Question 5

In the following equation, what is the Message function? `h = sigmoid( W * CONCAT( h_i ; (1/N_i) SUM_j (h_j) ) )`
- [ ] h_j
- [ ] CONCAT( h_i ; (1/N_i) SUM_j (h_j) )
- [ ] SUM_j (h_j)
- [ ] sigmoid( W * CONCAT( h_i ; (1/N_i) SUM_j (h_j) ) )

### Question 6

Structural information can be lost as a result of which function?
- [ ] The message function
- [ ] The aggregation function
- [ ] The update function
- [ ] The propagation function

### Question 7

Repeated applications of message passing can result in...
- [ ] Discontinuities
- [ ] Over-smoothing
- [ ] High variance in embeddings


## Digging Deeper
- Gilmer, Justin, et al. "Neural message passing for quantum chemistry." International conference on machine learning. PMLR, 2017. ([arXiv](https://arxiv.org/abs/1704.01212))
- Battaglia, P. et al. “Relational inductive biases, deep learning, and graph networks.” ArXiv abs/1806.01261 (2018): n. pag. ([arXiv](https://arxiv.org/abs/1806.01261))