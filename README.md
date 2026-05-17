# Lab11-K-Means-Credit-Card-Customer-Segmentation-using-K-Means

## Project Overview
This project applies K-Means clustering to segment credit card customers based on their financial behavior and transaction patterns.

The goal is to identify different customer groups that can help businesses improve marketing strategies and customer relationship management.

---

## Dataset
The dataset contains customer credit card information such as:
- Balance
- Purchases
- Cash Advance
- Payment Frequency
- Credit Limit
- Purchase Frequency
- Installment Purchases
- And other financial features

---

## Project Steps
1. Data Exploration
2. Data Cleaning
3. Handling Missing Values
4. Feature Scaling
5. Applying K-Means Clustering
6. Finding the Optimal K using:
   - Elbow Method
   - Silhouette Score
7. Cluster Analysis
8. PCA Visualization

---

## Missing Values Handling
Missing values in:
- `CREDIT_LIMIT`
- `MINIMUM_PAYMENTS`

were handled using mean imputation.

---

## Final Model
- Selected Number of Clusters: **K = 3**
- Random State: `42`

The final K value was selected based on the elbow method and silhouette score results.

---

## Cluster Summary
### Cluster 0
Customers with high cash advance usage and moderate purchasing activity.

### Cluster 1
High-value and highly active customers with high purchases and transaction frequency.

### Cluster 2
Customers with lower balances and lower overall activity.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
