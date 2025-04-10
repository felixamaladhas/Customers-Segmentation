# Customers-Segmentation

Presentation Link: [Customer Segmentation.pptx](https://github.com/user-attachments/files/19687141/Customer.Segmentation.pptx)

# Objective

This case requires to develop a customer segmentation to understand customers behavior and sepparate them in different groups or cluster according to their preferences, and once the division is done, this information can be given to marketing team so they can plan the strategy accordingly.
# Problem statement
This project uses unsupervised learning (K-Means & Hierarchical Clustering) to analyze customer purchasing data and segment them based on behavior. The goal is to uncover patterns, group similar customers, and assign scores to support targeted marketing and business strategies.

# Business Understanding

Clustering, an unsupervised machine learning technique, is employed for customer segmentation. Clustering aims to discover inherent groups or clusters within data, without prior knowledge of their existence. The following highlights the advantages and disadvantages of utilizing clustering for customer segmentation.

Advantages:
  * Reveals hidden or unexpected customer groups
  * Flexible and adaptable to various datasets
  * Requires less domain-specific expertise
  * Fast and scalable for large datasets
    
Disadvantages:
  * Clusters may be hard to interpret
  * Limited value if behavior data is missing

# Data Description

The sample Dataset summarizes the usage behavior of about 200 active customers during the last 3 months. The file is at a customer level with 5 behavioral variables.

Dataset Link: https://www.kaggle.com/datasets/shrutimechlearn/customer-data/data

# Processing of Analysis
1. Data Collection
Gather transactional data (e.g., invoices, purchase history).

2. Data Preprocessing
Clean data, handle missing values, and format dates and customer IDs.

3. Feature Engineering
Perform RFM analysis (Recency, Frequency, Monetary) to extract customer behavior metrics.

4. Normalization
Scale features to ensure equal weight in clustering algorithms.

5. Clustering
Apply K-Means and Hierarchical Clustering to group similar customers.

6. Cluster Evaluation
Use Elbow Method and Dendrograms to determine optimal clusters.

7. Visualization & Interpretation
Visualize clusters and assign labels/scores based on business insights.

# Conclusion
By applying unsupervised learning techniques like K-Means and Hierarchical Clustering, this project successfully segmented customers based on purchasing behavior. These clusters provide valuable insights into customer patterns, enabling businesses to personalize marketing strategies, improve customer engagement, and drive growth. Clustering proves to be a powerful, scalable tool for uncovering hidden patterns in customer data—turning raw transactions into strategic decisions.
