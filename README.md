# Clustering with K-Means

## Overview

This repository contains the solution for Task 8: Clustering with K-Means, using the Mall Customers dataset. The objective is to perform unsupervised learning to segment customers based on their annual income and spending score, and to evaluate the quality of clustering using common metrics and visualization techniques[1].

---

## Tools & Libraries Used

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

---

## Steps Involved in Task Completion

1. **Load and Inspect the Dataset**
   - Loaded the dataset using pandas and explored its structure.

2. **Feature Selection**
   - Selected 'Annual Income (k$)' and 'Spending Score (1-100)' as features for clustering.

3. **Data Visualization**
   - Plotted the data to visualize customer distribution.

4. **Finding Optimal Number of Clusters (K)**
   - Used the Elbow Method to determine the optimal value for K by plotting inertia for K=1 to K=10[1].

5. **K-Means Clustering**
   - Applied K-Means clustering using scikit-learn.
   - Assigned cluster labels to each customer.

6. **Cluster Visualization**
   - Visualized the resulting clusters with color-coding and marked cluster centroids.

7. **Cluster Evaluation**
   - Calculated the Silhouette Score to assess clustering quality.

---

## Results

- **Optimal K:** Determined using the Elbow Method plot.
- **Silhouette Score:** Indicates how well-separated and cohesive the clusters are.
- **Cluster Visualization:** Shows distinct customer segments in the income-spending score space.








