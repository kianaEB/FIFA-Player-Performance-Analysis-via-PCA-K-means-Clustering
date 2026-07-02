# FIFA Player Performance Analysis - PCA + K-means

Unsupervised analysis that groups football players by playstyle using dimensionality reduction and clustering.

## Overview
Starting from high-dimensional FIFA player attribute data, the project reduces dimensionality with PCA, compares players via Euclidean distance, and clusters them into playstyle groups with K-means.

## Approach
1. **Preprocessing** - select and scale player attributes.
2. **PCA** - reduce dimensionality while retaining most of the variance; enables 2D/3D visualization.
3. **Similarity** - compare players using Euclidean distance in the reduced space.
4. **K-means clustering** - group players with similar playstyles and interpret the clusters.

## Tech stack
Python, NumPy, Pandas, scikit-learn (PCA, KMeans), Matplotlib. Jupyter Notebook.

## Repo contents
- `FIFA_Analysis.ipynb` - full analysis and visualizations.

## Run it
```
pip install numpy pandas scikit-learn matplotlib
jupyter notebook
```
