### Question 1

Which of these is NOT a standard function in the Neural Message Passing framework?
- [ ] Update
- [x] Propagation
- [ ] Aggregation
- [ ] Message

### Question 2

The Message function can operate on which inputs? (Select all that apply)
- [x] The source node features
- [x] The destination node features
- [x] The edge features
- [ ] The aggregate of neighborhood messages

### Question 3

If you shuffle the order of the messages, the Aggregation function returns...
- [x] The same output
- [ ] Different output

### Question 4

The Update function can operate on which inputs? (Select all that apply)
- [ ] The source node features
- [x] The destination node features
- [ ] The edge features
- [ ] The multiset of messages
- [x] The aggregate of neighborhood messages

### Question 5

In the following equation, what is the Message function? `h = sigmoid( W * CONCAT( h_i ; (1/N_i) SUM_j (h_j) ) )`
- [x] h_j
- [ ] CONCAT( h_i ; (1/N_i) SUM_j (h_j) )
- [ ] SUM_j (h_j)
- [ ] sigmoid( W * CONCAT( h_i ; (1/N_i) SUM_j (h_j) ) )

### Question 6

Structural information can be lost as a result of which function?
- [ ] The message function
- [x] The aggregation function
- [ ] The update function
- [ ] The propagation function

### Question 7

Repeated applications of message passing can result in...
- [ ] Discontinuities
- [x] Over-smoothing
- [ ] High variance in embeddings