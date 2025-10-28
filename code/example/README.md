## This folder contains testing of various ways of working with biomolecules and developing ML and DL models

#### Packages:
- Biopython: Has functionalities for working with biological data, can parse FASTA, PDB files etc. 

- RDKit: Enables calculations of chemical properties such as weight, volume, n atoms, charge etc 

- Scikit.learn: Some standard ML models

- torch & torch geometric: For custom development of NN and ML architecture 

## Links to useful sites and tutorials

Playground for **simple** neural networks:
https://playground.tensorflow.org/

Understanding Backpropagation:
https://karpathy.medium.com/yes-you-should-understand-backprop-e2f06eab496b

Getting started on graph neural networks:
https://distill.pub/2021/gnn-intro/

Torch geometric:

https://pytorch-geometric.readthedocs.io/en/latest/

Biopython:

https://biopython.org/docs/latest/Tutorial/ , 
https://biopython.org/docs/latest/Tutorial/chapter_pdb.html


## Things to consider when training networks
- What does our training, validation and test data look like? 
- Are the distributions similar, is there leakage between the datasets?

- Loss function: How is the network learning "right" and "wrong"

- Architecture: Start simple and increase complexity 