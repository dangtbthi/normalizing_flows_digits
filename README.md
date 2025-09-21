# Normalizing Flows on Digits Dataset

## Project Overview
This is a simple implementation of normalizing flow (affine coupling layer) concepts, created for the PiMA The Mathematics of Generative Models Summer Program 2025 project to illustrate the methodology on the scikit-learn Digits dataset. 
Special thanks to the instructors and fellow participants for discussions and collaboration, as this was not an individual project.  

## Methods
Normalizing Flows transform a simple base distribution (in this project I use standard logistic distribution) into a complex target distribution via a sequence of invertible mappings, enabling:
- **Exact log-likelihood** computation for training
- **Sampling** to generate new data

## References
1. George Papamakarios, et al. Normalizing Flows for Probabilistic Modeling and Inference. 2021. [https://arxiv.org/abs/1912.02762](https://arxiv.org/abs/1912.02762)
2. PiMA The Mathematics of Generative Models online course

