# Decomposition Techniques for Dimensionality Reduction

Study **Decomposition Techniques** notebook! This Jupyter Notebook explores several foundational and advanced dimensionality reduction methods used in machine learning and data science for simplifying data and extracting meaningful structures.

## Overview

The notebook covers the following decomposition techniques:

| Technique | Type | Description |
|----------|------|-------------|
| **PCA** *(Principal Component Analysis)* | Linear | Simplifies data while preserving maximum variance. Great for preprocessing and compression. |
| **SVD** *(Singular Value Decomposition)* | Linear | Decomposes matrices to simplify data. Useful for noise reduction and latent structure discovery. |
| **NMF** *(Non-negative Matrix Factorization)* | Linear (Non-negative) | Represents data as additive combinations of parts. Especially useful for interpretability in text and images. |
| **FA** *(Factor Analysis)* | Linear | Identifies latent factors and accounts for noise. Widely used in social sciences and psychology. |
| **UMAP** *(Uniform Manifold Approximation and Projection)* | Non-linear | Preserves local and global structure in data. Excellent for high-dimensional data visualization. |

## Visualizations

Each technique includes Python implementations and intuitive 2D/3D visualizations using libraries like `matplotlib` and `sklearn`.

## Dependencies

Before running the notebook, make sure you have the following Python packages installed:

```bash
pip install numpy pandas matplotlib scikit-learn umap-learn
```

## Usage

1. Clone the repository or download the notebook.
2. Open `decomposition_techniques.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells to explore how each technique works on sample datasets.


## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
