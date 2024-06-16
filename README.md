# Image Denoising using Learned Robust Principal Component Analysis
This course design project explores Principal Component Analysis (PCA), Robust PCA (RPCA), and the advanced Learned RPCA (LRPCA) algorithms, analyzing their theoretical foundations, performance, and application to real-world data scenarios. It combines classical statistical learning with modern optimization and deep learning-based improvements.

# Author
![Xue Yuhan](https://felisevan.net)

## Overview
Traditional PCA is widely used for dimensionality reduction but is sensitive to noise and outliers. RPCA improves robustness by separating data into low-rank and sparse components. However, it suffers from high computational cost due to repeated Singular Value Decompositions (SVD). Learned RPCA (LRPCA) addresses this challenge with differentiable approximations that are scalable and trainable.

Core file are: 
* `experiment.ipynb`: Doing comparsion and visualization
* `training_codes.py`: Training model
* `v1.pptx`: Powerpoint used in class oral presentation

## Key Topics
PCA: Linear dimensionality reduction via eigenvalue decomposition of the covariance matrix.

RPCA: Decomposes data matrix into low-rank + sparse components to handle outliers.

LRPCA: Learns an efficient and differentiable approximation to RPCA, avoiding expensive SVD steps.

## Data Mining Concepts Covered
Noise Handling: Robustness against data corruption and outliers.

Curse of Dimensionality: High-dimensional data sparsity challenges.

Z-Score Normalization: Feature standardization for consistent scaling.

Gradient Descent: Optimization technique for training learning-based models.

## Experiments
PCA on raw and normalized data

RPCA implementation

LRPCA implementation

Image reconstruction with added noise

Visual and performance comparison across algorithms

## Tools & Libraries
Python

NumPy, SciPy

scikit-learn

Matplotlib for visualization

## Results
PCA is fast but fails with noisy data.

RPCA performs well with noise but is computationally intensive.

LRPCA achieves competitive performance with lower runtime and better scalability.

## Conclusion
This course design highlights the trade-offs between interpretability, robustness, and efficiency in dimensionality reduction techniques. LRPCA emerges as a promising approach for large-scale or noisy data tasks, offering both performance and practical scalability.