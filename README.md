# KMeans Clustering Visualization

This repository contains a simple Python script demonstrating the application of KMeans clustering on a synthetic dataset and its visualization using matplotlib.

## Overview

The script performs the following steps:

1. **Generates a synthetic dataset:** Uses `sklearn.datasets.make_blobs` to create a 2D dataset with 300 data points, distributed into 3 clusters.
2. **Applies KMeans clustering:** Utilizes `sklearn.cluster.KMeans` to cluster the generated data into 3 groups.
3. **Visualizes the results:** Creates a scatter plot using `matplotlib.pyplot` to show:
    * The data points, colored according to their assigned cluster.
    * The cluster centers, marked as red 'x's.

## Requirements

To run this code, you'll need the following Python libraries:

* scikit-learn (`sklearn`)
* matplotlib (`matplotlib`)
* NumPy (`numpy`) (scikit-learn and matplotlib typically depend on NumPy)

You can install these libraries using pip:

```bash
pip install scikit-learn matplotlib numpy
