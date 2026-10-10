# Customer Segmentation

The objective of this project is to perform customer segmentation using unsupervised learning techniques. The goal is to identify distinct behavioral groups within the customer base in order to better target marketing and commercial actions.

## Objectives
* Understand customer purchasing behavior patterns.
* Identify high-value (VIP) customers and those with low potential value.
* Guide and support targeted marketing strategies.
* Improve customer retention and optimize revenue.

## Data
This project relies on the **Online Retail** dataset, which contains transaction logs from an online retail store.

## Methodology

The analytical process follows these steps:
1. **Exploratory Data Analysis (EDA) & Cleaning**: Filtering out negative quantities and handling missing values to ensure data quality.
2. **Feature Engineering**: Creating an enriched RFM matrix per customer, calculating for each:
   - **Recency**: Number of days elapsed since the last purchase.
   - **Frequency**: Number of unique invoices/orders per customer.
   - **Monetary**: Total amount spent.
   - **TotalQuantity**: Total volume of products purchased.
3. **Dimensionality Reduction & Clustering**: Standardizing the data, applying algorithms like K-Means or DBSCAN, coupled with dimensionality reduction techniques such as PCA (Principal Component Analysis) or t-SNE to visualize the clusters.
4. **Evaluation**: Verifying cluster cohesion using the Silhouette score.

## Technologies Used
* **Language**: Python
* **Data Manipulation**: Pandas, NumPy
* **Machine Learning**: Scikit-Learn (KMeans, DBSCAN, PCA, TSNE, StandardScaler)
* **Visualization**: Matplotlib, Seaborn

## Project Files
* `exploration.ipynb`: The Jupyter notebook containing all the data cleaning, exploration, and clustering model training.
* `Online Retail.xlsx` & `Online Retail.xlsx - Online Retail.csv`: The transactional data sources.
