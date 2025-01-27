# E-commerce Transaction Analysis

This repository contains code and data for exploratory data analysis (EDA), customer segmentation (clustering), and lookalike modeling on an e-commerce dataset.

## Repository Structure

```
k-jaswanth-kumar-ecommerce-transaction-analysis/
├── Customers.csv
├── Jaswanth_Kumar_Malla_Clustering.ipynb
├── Jaswanth_Kumar_Malla_EDA.ipynb
├── Jaswanth_Kumar_Malla_Lookalike.csv
├── Jaswanth_Kumar_Malla_Lookalike.ipynb
├── Products.csv
└── Transactions.csv
```

### Data Files
1. **Customers.csv**  
   Contains customer information such as CustomerID, CustomerName, Region, and SignupDate.

2. **Products.csv**  
   Contains product details including ProductID, ProductName, Category, and Price.

3. **Transactions.csv**  
   Contains transaction records (TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, and Price).

4. **Jaswanth_Kumar_Malla_Lookalike.csv**  
   Output file from the lookalike model indicating top similar customers and their similarity scores.

### Notebooks

1. **Jaswanth_Kumar_Malla_EDA.ipynb**  
   - Performs exploratory data analysis on the merged dataset (customers, products, and transactions).  
   - Covers missing values, descriptive statistics, time-based analysis, revenue breakdown by region, product category preferences, monthly revenue trends, etc.

2. **Jaswanth_Kumar_Malla_Clustering.ipynb**  
   - Demonstrates customer segmentation using K-Means clustering.  
   - Uses key features (e.g., number of transactions, total spend, recency, days since signup) to cluster customers.  
   - Evaluates cluster performance with metrics like Davies-Bouldin Index and silhouette score.  
   - Provides visualizations (PCA plot, box plots) to interpret segment characteristics.

3. **Jaswanth_Kumar_Malla_Lookalike.ipynb**  
   - Builds a lookalike model to identify similar customers based on product category purchase behavior and demographic/region features.  
   - Uses cosine similarity on standardized features.  
   - Produces the `Jaswanth_Kumar_Malla_Lookalike.csv` file with top matches for target customers.



---
