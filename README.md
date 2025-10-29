## Overview

This repo represents the full content of the Introduction to Graph Neural Networks course by Zak Jost / WelcomeAIOverlords.  It has a mix of theory, hands-on exercises, and discussions of practical considerations when building real GNN systems.  Each of these three sections are mostly self-contained and can be taken independently of the others.

## Theory 

The [Theory section](./theory/) of the course covers the foundations of graph neural networks.  We discuss the message passing framework and how this addresses the many challenges that arise from symmetries in graphs.  We work our way up to understanding convolutions on graphs, and where they come from.

| Lecture                                                  | Video   | Slides | Directory |
|----------------------------------------------------------|---------|--------|-----------|
| Neural Message Passing                                   | [YouTube](https://youtu.be/foe5H9AG_4M) | [link](https://drive.google.com/file/d/1R7y4QMi7Vo5y_M-kGDvuvIJ_vNFrAX3k/view?usp=drive_link)   | [path](./01_neural_message_passing/)      |
| Permutation Symmetries                                   | [YouTube](https://youtu.be/QldU0IbhlMg) | [link](https://drive.google.com/file/d/1KWnxp8XJkbY0x1eABn2gTOvqZN6nbRd_/view?usp=drive_link)   | [path](./02_permutation_symmetries/)      |
| Graph Isomorphism                                        | [YouTube](https://youtu.be/l-Q9AQZeq2E) | [link](https://drive.google.com/file/d/1J9s6QYveNQVBp_VXRrRUojmBwJYJPlw7/view?usp=sharing)   | [path](./03_graph_isomorphism/)      |
| How Powerful are GNNs?                                   | [YouTube](https://youtu.be/fDgMLidNLN8) | [link](https://drive.google.com/file/d/1ne32P2p_knZgzCO4_Gifvj-AYvwZXVXQ/view?usp=sharing)   | [path](./04_how_powerful_are_gnns/)      |
| The Graph Laplacian                                      | [YouTube](https://youtu.be/1OLL7bwJRjY) | [link](https://drive.google.com/file/d/1RXtFA7Fd2dFc4075baZ8YNLLgvNfT5ek/view?usp=sharing)   | [path](./05_graph_laplacian/)      |
| Fourier Transforms, Wavelets, and Convolutions on Graphs | [YouTube](https://youtu.be/ScmpdfBnfUE) | [link](https://drive.google.com/file/d/1TITdMnWEIObP6MRWx5SJ6ucpEf9FfiVm/view?usp=sharing)   | [path](./06_fts_wavelets_convolutions/)      |
| The Math of Graph Convolutional Networks                 | [YouTube](https://youtu.be/JA3LpaoyrZ0) | [link](https://drive.google.com/file/d/1eBZlxtC7gYiObY9ItIBa99OSkvqYON9D/view?usp=sharing)   | [path](./07_math_of_gcns/)      |

## Hands-on

The [Hands-on section](./hands_on/) consists of 3 main application areas: Node Classification, Link Prediction, and Graph Classification.  Each section contains:

* An overview video that introduces the problem framing
* A template notebook with "TODO" comments that indicate the sections that need filled in
* An answer key notebook where the TODO sections are filled in with correct answers
* A solution walk-thru video that explains the answer key

| Domain               | Overview video | Slides   | Exercise notebook | Answer key notebook | Solution walk-thru |
|----------------------|----------------|----------|-------------------|---------------------|--------------------|
| Node Classification  | [YouTube](https://youtu.be/YbgrlonXfwc)    | [link](https://drive.google.com/file/d/1_v3GbOz3rtwuacwnKBd9s3Ifrs8BixPq/view?usp=sharing) | [exercise](./01_node_classification/problem.ipynb)      | [answer key](./01_node_classification/answer.ipynb)      | [YouTube](https://youtu.be/57lOCJwo9zc)        |
| Link Prediction      | [YouTube](https://youtu.be/wt2Ei8Z6tL4)    | [link](https://drive.google.com/file/d/1mbgg2MNT8-cw9ZNuzyKxAaQzeXYD9qvG/view?usp=sharing) | [exercise](./02_link_prediction/problem.ipynb)      | [answer key](./02_link_prediction/answer.ipynb)      | [YouTube](https://youtu.be/2wUurnbwXIY)        |
| Graph Classification | [YouTube](https://youtu.be/4JI5N-JXKGc)    | [link](https://drive.google.com/file/d/1zQ_pGmArnNXX6H19HDyPNvhMHY0AZRGU/view?usp=sharing) | [exercise](./03_graph_classification/problem.ipynb)      | [answer key](./03_graph_classification/answer.ipynb)      | [YouTube](https://youtu.be/HCUqVL0TKkw)        |

## Practical considerations 

The [Practical considerations](./practical.md) section covers a number of common practical issues that need to be understood for most practical applications of GNNs.

| Topic                             | Video   | Slides |
|-----------------------------------|---------|--------|
| Tools of the trade                | [YouTube](https://youtu.be/WHDXDMJZywU) | [link](https://drive.google.com/file/d/15EoDT-Q6smUj_gslL72vkBg05klTarr2/view?usp=sharing)   |
| Transductive vs Inductive         | [YouTube](https://youtu.be/TnseXMkW1YU) | [link](https://drive.google.com/file/d/1LXgoWCwAjPxtEJ_eIJGlOH1a_w0ldTcU/view?usp=sharing)   |
| Over-squashing and Over-smoothing | [YouTube](https://youtu.be/egU3zGEzYjw) | [link](https://drive.google.com/file/d/1y8ew_qi4xgHVGdl6ev0sTgCaQ6rGPsAB/view?usp=sharing)   |
| Improving scalability             | [YouTube](https://youtu.be/iahcDPtcoAw) | [link](https://drive.google.com/file/d/1sFUxK1CqXJRV5D2EHLFCwaEMwnR2TMAx/view?usp=sharing)   |
