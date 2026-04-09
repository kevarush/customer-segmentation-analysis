# customer-segmentation-analysis
Customer segmentation using K-means clustering in Python to identify behavior-based marketing groups.
# Customer Segmentation Analysis Using K-Means Clustering

## Project Overview
This project uses K-means clustering to segment customers based on annual income and spending score. The goal is to identify meaningful customer groups that can help businesses improve marketing strategies, customer targeting, and overall decision-making.

## Objective
- Segment customers into distinct groups based on purchasing-related behavior
- Use the elbow method to determine an appropriate number of clusters
- Interpret the business meaning of each segment

## Dataset
- **Source:** Mall Customers dataset
- **Features used for clustering:**
  - Annual Income (k$)
  - Spending Score (1-100)

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded and explored customer data
2. Reviewed summary statistics and distributions
3. Visualized relationships between annual income and spending score
4. Standardized the clustering variables using `StandardScaler`
5. Applied the elbow method to evaluate the optimal number of clusters
6. Built a K-means clustering model with 5 customer segments
7. Visualized the resulting customer groups
8. Interpreted cluster patterns for business decision-making

## Key Findings
The elbow method suggested that 4–5 clusters provided a good balance between simplicity and segmentation performance. A 5-cluster solution was selected.

The analysis identified the following customer groups:

- **High income, high spending:** premium / VIP customers
- **High income, low spending:** wealthy but cautious customers
- **Low income, high spending:** highly engaged or impulsive spenders
- **Low income, low spending:** budget-conscious customers
- **Mid income, moderate spending:** average, stable customers

## Business Insights
These segments can support targeted marketing strategies such as:
- offering loyalty rewards to high-income, high-spending customers
- using promotions to encourage high-income, low-spending customers to purchase more
- maintaining engagement with moderate spenders through consistent campaigns
- limiting marketing spend on lower-value customer groups when appropriate

## Sample Cluster Summary
| Cluster | Avg. Annual Income (k$) | Avg. Spending Score |
|--------|--------------------------|---------------------|
| 0 | 122.67 | 29.75 |
| 1 | 33.23 | 85.38 |
| 2 | 45.60 | 15.45 |
| 3 | 57.84 | 55.74 |
| 4 | 111.42 | 78.21 |

## Visualizations

### Elbow Method
![Elbow Method](elbow_method.png)

### Customer Segments
![Customer Segments](customer_segments.png)

## Conclusion
This project demonstrates how unsupervised machine learning can be used to uncover customer behavior patterns and generate actionable business insights. K-means clustering provided a simple but effective way to identify segments that could support more personalized and strategic marketing decisions.
