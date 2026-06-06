# Spotify Clustering & PCA Analysis

Unsupervised analysis of the Spotify 2023 dataset using hierarchical clustering and PCA to find and visualise patterns in track audio features.

## Methods

- Data cleaning: categorical encoding, mean imputation, feature scaling
- Hierarchical clustering (Ward's method) with dendrogram
- Optimal cluster count via silhouette score
- PCA for dimensionality reduction (2D projection, scree plot, biplot)

## Outputs

- Dendrogram of hierarchical relationships
- PCA scatter plot of clusters in 2D
- Silhouette score analysis
- Scree plot of explained variance

## Structure

```
main.py          Pipeline entry point
functii.py       Data preprocessing helpers
grafice.py       Plotting (dendrogram, biplot, silhouette)
spotify-2023.csv Dataset
```

## Setup

```sh
pip install pandas matplotlib seaborn scikit-learn scipy numpy
git clone https://github.com/aariton/Spotify_project.git
cd Spotify_project
python main.py
```

**Author:** Alexandru Ariton
