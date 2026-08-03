# Week 3: Clustering Models & Association Rule Mining

## Overview
This week focused on unsupervised learning techniques to discover hidden patterns within real-world business datasets. The project is split into two core applications: Customer Segmentation and Market Basket Analysis.

## Part 1: Customer Segmentation (Clustering)
Using a Mall Customer dataset, multiple distance-based and density-based algorithms were applied to group customers based on Age, Annual Income, and Spending Score.
*   **Algorithms Applied:** K-Means (optimized via Elbow Method), Agglomerative Hierarchical (using Ward Linkage Dendrograms), and DBSCAN.
*   **Findings:** K-Means identified 5 distinct customer profiles. The most valuable segment ("High Income / High Spending") is hypothesized to be driven by exclusive retail experiences and brand loyalty, presenting a clear target for VIP marketing campaigns.

## Part 2: Market Basket Analysis (Association Rules)
Using a real Groceries transactional dataset, rule mining was applied to find items frequently bought together to inform store layout and bundling strategies.
*   **Algorithms Applied:** Apriori and FP-Growth.
*   **Findings:** Strong rules with high "Lift" scores were discovered, indicating products that heavily drive the sales of companion items. Furthermore, the **FP-Growth** algorithm proved to be significantly faster and more computationally efficient than Apriori by avoiding repeated database scans and candidate generation.

## Files in this Directory
*   `week3_clustering.ipynb` - Unsupervised clustering and segmentation.
*   `week3_association_rules.ipynb` - Frequent itemset and rule generation.
*   `requirements.txt` - Project dependencies.
