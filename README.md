# Generative Quantum Principal Component Analysis
Haimeng Zhao and Weixiao Sun

## Declaration
This is a course project for Quantum Artificial Intelligence course given by Prof. Dongling Deng at Tsinghua University in 2021 Fall. 

The repository contains code for implementing a quantum generative model with quantum principal component analysis via PennyLane and TensorFlow. A detailed document can be found under the name `paper.pdf`. 

However, it turns out that this work is covered by [an existing work](https://iopscience.iop.org/article/10.1088/2632-2153/aba19d) from a different perspective which we were not aware of.

We open source the code anyway, hoping it might help others in their implementation of works in quantum generative learning. Note that the paper is not peer reviewed and we do not guarantee the correctness. If you find this repository useful, please cite us using the citation button in the right column provided by GitHub.

## Abstract
Generative learning is a major branch of machine learning which has yielded significant applications in a wide range of areas. Quantum generative learning utilizes the power of quantum computers to learn and generate quantum data, demonstrating potential supremacy over its classical counterpart. Here, we propose a simple yet powerful generative model based on variational quantum principal component analysis (G-qPCA), which extracts the leading eigenvalues and corresponding eigenvectors of a given quantum state via a parameterized quantum circuit, and generates data by preparing the state accordingly. Recognizing the linearity of quantum mechanics and optimality of qPCA in state discrimination, we further discover that three mainstream generative models in the classical literature can be unified in the quantum regime and reduced to our algorithm. Along the way, we propose a fully quantum formulation of variational autoencoder and introduce the quantum version of normalizing flow. Our algorithm is demonstrated with numerical simulations and experimentally implementable on noisy intermediate-scale quantum devices, while free from the use of quantum random access memory which is a caveat in most quantum machine learning algorithms.
