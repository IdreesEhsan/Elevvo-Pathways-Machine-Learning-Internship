🛍️ Customer Segmentation with KMeans and DBSCAN

This project applies unsupervised learning techniques to the Mall Customers dataset to perform customer segmentation. The goal is to group customers based on their Annual Income and Spending Score for better business insights.

🔧 Libraries Used

Python

Pandas → Data handling

Matplotlib → Visualizations

Scikit-learn → KMeans, DBSCAN, StandardScaler, Silhouette Score

📊 Steps Performed

Load dataset (Mall_Customers.csv).

Select relevant features:

Annual Income (k$)

Spending Score (1-100)

Scale features using StandardScaler.

KMeans Clustering

Find optimal k using Elbow Method and Silhouette Score

Visualize results in 2D scatter plots

DBSCAN Clustering

Apply density-based clustering

Compare results with KMeans (detects noise and irregular clusters)

Analyze clusters: compute average income and spending per cluster.

📈 Results

KMeans produced clear, spherical clusters useful for business segmentation.

DBSCAN identified clusters of varying shapes and flagged noise points.

Both approaches highlight groups like:

High income, high spenders

Low income, low spenders

Moderate income, balanced spenders
