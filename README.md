# Introduction
In this notebook, we explore the differences between Standard Parametrization (SP) and Maximal Update Parametrization (μP) in the context of training neural networks. We aim to understand how μP affects the training process, and if it offers any advantages over traditional methods.

The key focal point of this analysis is to validate the hypothesis that *Wider is always better* under the μP framework and to demonstrate the hyperparameter stability that μP claims to offer.

This will be demonstrated using a case study with the well-known CIFAR10 dataset.

## Ressources : 
Here are the links to the original paper and code repository:
- **Article**: [Understanding the Role of Training Regimes in Continual Learning](https://arxiv.org/abs/2203.03466)
- **Code**: [Microsoft's μP GitHub Repository](https://github.com/microsoft/mup)
