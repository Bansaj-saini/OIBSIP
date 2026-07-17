# Customer Segmentation using K-Means

# Project Overview
This project performs **customer segmentation** using the K-Means clustering algorithm on an e-commerce dataset.  
The aim is to group customers based on their purchasing behavior and generate actionable marketing strategies.

# Objective
- Segment customers into distinct groups
- Analyze purchasing patterns using RFM (Recency, Frequency, Monetary)
- Provide data-driven marketing recommendations

# Dataset Description
The dataset contains customer behavior information, including:

- Customer ID
- Days Since Last Purchase (Recency)
- Items Purchased (Frequency)
- Total Spend (Monetary)
- Additional attributes (Age, Gender, etc.)

# Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (K-Means, StandardScaler)
- Jupyter Notebook

# Workflow

1. Data Loading & Exploration
- Loaded dataset using Pandas
- Checked for missing values
- Performed statistical analysis

2. Feature Selection (RFM Analysis)
- Recency → Days Since Last Purchase
- Frequency → Items Purchased
- Monetary → Total Spend

3. Data Preprocessing
- Standardized features using StandardScaler
- Prepared data for clustering

4. Finding Optimal Clusters
- Used Elbow Method
- Selected optimal number of clusters (K = 3)

5. K-Means Clustering
- Applied K-Means algorithm
- Assigned cluster labels to customers

6. Visualization
- Scatter plots:
  - Frequency vs Monetary
  - Recency vs Monetary

7. Cluster Profiling
- Calculated mean values per cluster
- Interpreted customer segments

## Customer Segments

# Cluster 0 – Premium Customers
- High spending
- Frequent purchases
- Recently active

# Marketing Strategy:
- Loyalty programs
- Exclusive offers
- Personalized recommendations

# Cluster 1 – Regular Customers
- Moderate spending
- Average purchase frequency

# Marketing Strategy:
- Discounts and bundle offers
- Upselling and cross-selling

# Cluster 2 – Low-Value Customers
- Low spending
- Less frequent purchases
- Inactive recently

# Marketing Strategy:
- Re-engagement campaigns
- Coupons and promotional offers

# Key Insights
- Customer segmentation improves targeted marketing
- High-value customers should be retained
- Medium-value customers can be converted to premium
- Low-value customers need cost-effective engagement

# Conclusion
K-Means clustering successfully grouped customers into meaningful segments.  
This helps businesses improve marketing strategies, customer retention, and revenue growth.

# Future Scope
- Use advanced clustering techniques (DBSCAN, Hierarchical)
- Include more features like location and product categories
- Implement real-time segmentation systems