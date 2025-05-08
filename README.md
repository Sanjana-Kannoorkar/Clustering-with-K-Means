# Clustering-with-K-Means

## Objective
Perform unsupervised learning using K-Means clustering on a customer segmentation dataset.

## Dataset
- `Mall_Customers.csv`  
- Features used: `Annual Income (k$)` and `Spending Score (1-100)`

## Steps

1. **Load and Preprocess the Data**
   - Load the dataset and select relevant features.

2. **Determine Optimal K**
   - Use the **Elbow Method** to identify the optimal number of clusters.

3. **Apply K-Means Clustering**
   - Fit the KMeans model using the optimal K.
   - Assign cluster labels to each data point.

4. **Evaluate Clustering**
   - Use **Silhouette Score** to evaluate the quality of clustering.

5. **Visualize Clusters**
   - Scatter plot with color-coded clusters.

## Evaluation
- **Elbow Method** helps choose the ideal number of clusters.
- **Silhouette Score** provides clustering quality.

## Output Example
- Elbow Curve (Inertia vs K)
- Scatter plot of clusters by `Annual Income` vs `Spending Score`
- Silhouette Score printed in the console
