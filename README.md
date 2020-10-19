# Autoencoders that don't overfit towards the Identity

This notebook provides an implementation in Python 3.7.7 (and Tensorflow 1.15.0) of the algorithms outlined in the paper 
"Autoencoders that don't overfit towards the Identity" 
at the 34th Conference on Neural Information Processing Systems (NeurIPS 2020).

For reproducibility, the experiments utilize publicly available [code](https://github.com/dawenl/vae_cf) for pre-processing three popular data-sets and for evaluating the learned models. That code accompanies the paper "[Variational autoencoders for collaborative filtering](https://arxiv.org/abs/1802.05814)" by Dawen Liang et al. at The Web Conference 2018. While the code for the Movielens-20M data-set was made publicly available, the code for pre-processing the other two data-sets can easily be obtained by modifying their code as described in their paper.
The experiments were run on an AWS instance with 128 GB RAM and 16 vCPUs.
