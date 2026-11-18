# Smart Cart Customer Segmentation

Unsupervised machine learning project that groups supermarket customers into segments based on their demographics and spending behaviour, so marketing can be targeted better.

## Dataset
'smartcart_customers.csv' has customer details such as birth year, education, marital status, income, children at home, recency and spending on product categories (wines, fish, sweets, etc.).

## Workflow
1. Data preprocessing
2. Feature engineering and dropping unneeded columns
3. Outlier handling
4. Correlation heatmap
5. Encoding of categorical features
6. Scaling
7. Visualization
8. Finding the optimal K (Elbow method with KneeLocator from 'kneed', and Silhouette score)
9. Clustering with K-Means and Agglomerative Clustering
10. Characterization of clusters
11. Cluster summary

## Tech Stack
Python, pandas, matplotlib, seaborn, scikit-learn, kneed , Jupyter Lab

## Files
- 'Smart_Cart_MP.ipynb': main notebook
- 'smartcart_customers.csv': dataset

## Results
Customers were divided into **4 clusters**. Each cluster is profiled by income and spending pattern in the notebook.

## Author
Rishu Kumar Singh
