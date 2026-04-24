# Self-Pruning-Neural-Networks-Dynamic-Sparsity-Learning-for-Efficient-Image-Classification

1. Title
Self-Pruning Neural Networks: Dynamic Sparsity Learning for Efficient Image Classification

2. Description
This project implements a self-pruning neural network for CIFAR-10 classification, where learnable gate parameters enable dynamic removal of less important weights during training. Using L1 regularization, the model achieves sparsity while maintaining competitive accuracy, improving efficiency.

3. Methodology

Explain:

PrunableLinear layer
Gate mechanism (sigmoid)
L1 sparsity loss

4. Results Table (REQUIRED)

Example:

| Lambda | Accuracy (%)| Sparsity (%) |
|--------|-------------|--------------|
| 5e-6   | 55.29       | 39.36        |
| 1e-5   | 57.23       | 62.63        |
| 5e-5   | 56.50       | 87.19        |

5. Key Insight (VERY IMPORTANT)
Increasing λ:

increases sparsity
reduces accuracy
