# Normalizing Flows on Digits Dataset

A PyTorch implementation of **Normalizing Flows** (affine coupling layers) to model the probability distribution of the scikit-learn Digits dataset and generate digit-like samples.

## Overview
Normalizing Flows transform a simple base distribution (e.g., Gaussian/Logistic) into a complex target distribution via a sequence of invertible mappings, enabling:
- **Exact log-likelihood** computation for training
- **Sampling** to generate new data

## Pipeline
- **Data**: scikit-learn Digits (8×8 grayscale)
- **Preprocessing**: scaling/normalization
- **Model**: coupling layers + log-det-Jacobian
- **Training**: maximize log-likelihood (optimize NLL)
- **Evaluation**: average log-likelihood on test set + visual inspection of generated samples

## Results
- Trained flow generates digit-like images.
- Example samples: (assets/generated_digits.png)
