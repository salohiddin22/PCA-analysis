# Image Analysis with PCA

This repository contains two Jupyter notebooks that demonstrate how to analyze images using Principal Component Analysis (PCA). PCA is a powerful statistical technique used to emphasize variation and bring out strong patterns in a dataset. It is particularly useful in reducing the dimensionality of complex data, such as images, while preserving as much information as possible.

## Notebooks

### 1. Analyzing Transformer Features (`transformer_features_analysis.ipynb`)
This notebook shows how to extract features from images using a transformer model and then analyze those features using PCA. Transformers have become a state-of-the-art approach in various image analysis tasks. By applying PCA, we can visualize and understand the high-dimensional feature space produced by the transformer.

### 2. Analyzing Layer Features (`CNN_layer_features_analysis.ipynb`)
In this notebook, we demonstrate how to analyze features extracted from each layer of a neural network. The features are saved as `.pth` files, which are then loaded and analyzed using PCA. This approach helps in understanding the evolution of features as they pass through the layers of the network and how different layers contribute to the final representation.

## What is PCA?

Principal Component Analysis (PCA) is a dimensionality reduction technique that transforms data into a set of orthogonal (uncorrelated) components, ordered by the amount of variance they capture from the data. It is widely used for:
- Reducing the number of variables in data while retaining essential information.
- Visualizing high-dimensional data.
- Noise reduction and data compression.

For more detailed information about PCA, you can refer to this [comprehensive guide](https://en.wikipedia.org/wiki/Principal_component_analysis).

## Getting Started

To get started with these notebooks, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/salohiddin22/PCA-analysis
   cd PCA-analysis
