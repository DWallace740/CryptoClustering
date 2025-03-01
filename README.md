# Cryptocurrency Clustering using K-Means and PCA

## Overview
This project explores clustering techniques on cryptocurrency market data using **K-Means clustering**. It includes data preprocessing, scaling, Principal Component Analysis (PCA), and visualization to analyze the impact of dimensionality reduction on clustering results.

## Key Steps
1. **Data Preprocessing:**
   - Load cryptocurrency market data.
   - Clean and normalize the dataset.
2. **Elbow Method for Optimal k:**
   - Compute inertia values for different cluster sizes.
   - Visualize the Elbow Curve.
3. **K-Means Clustering:**
   - Apply K-Means to the scaled dataset.
   - Visualize cluster assignments.
4. **Dimensionality Reduction with PCA:**
   - Reduce features using PCA (3 components).
   - Reapply K-Means and visualize new clusters.
5. **Comparison of Clustering Results:**
   - Compare Elbow Curves (original vs. PCA data).
   - Compare clustering results using scatter plots.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy scikit-learn hvplot panel matplotlib
```

## Running the Notebook
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to `Crypto_Clustering_starter_code.ipynb` and execute each cell in sequence.
3. Review the visualizations and compare clustering results with and without PCA.

## Results & Insights
- The **Elbow Method** helps identify the optimal number of clusters.
- PCA **reduces dimensionality**, improving computational efficiency while maintaining clustering structure.
- Cluster comparison reveals how fewer features impact the grouping of cryptocurrencies.

## Next Steps
- Experiment with different PCA component values.
- Try additional clustering algorithms (DBSCAN, Agglomerative Clustering).
- Incorporate real-time crypto data for live clustering updates.

## Resources and Support

For this project, I used multiple resources to ensure the successful completion of the assignment:

ChatGPT (AI Assistant): For guidance on code logic, debugging, structuring the scripts, and formatting my README file.

All external resources used are listed here for transparency

## Author
This project is part of a **data analytics bootcamp** focusing on unsupervised machine learning techniques. Completed by Daena Wallace