# Seeds Clustering Using K-Means

This project uses unsupervised machine learning to group wheat seeds based on their measurements and see how closely the clusters match the real wheat varieties.

## Dataset

The Seeds dataset was loaded from OpenML and contains 210 wheat seeds with 7 measurements, including area, perimeter, compactness, length, width, asymmetry and groove length.

## Methods

- Data scaling
- PCA
- K-Means clustering
- Elbow method
- Silhouette score
- Cross-tabulation
- Purity score

## Results

The elbow method suggested 3 clusters, while the silhouette score was highest at 2. I chose 3 clusters.

The final clustering achieved a purity score of about 0.92, with 193 out of 210 seeds matching the main variety in their cluster.

## Files

- `Final_Project_Option3_Seeds_Clustering.ipynb` — full notebook with code and results
- `Final_Project_Option3_Portfolio.pdf` — short project report and key plots
