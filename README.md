# customer_segmentation
Cluster Analysis

Here is a visualization of the customer clusters obtained using t-SNE:

![Screenshot](https://github.com/PetyaPetrova96/customer_segmentation/raw/master/Screenshot%202024-09-18%20163810.png)

Cluster 0:

Recency: 4710.45 days (High)
Frequency: 3.61 purchases (Low)
Monetary: 1325.05 (Low)
Number of Customers: 3037 (Largest cluster)
Conclusion: This cluster has the highest number of customers but the lowest frequency and monetary values. Customers in this group are less frequent buyers and have spent less on average. The high recency indicates that they haven't made recent purchases.

Cluster 1:

Recency: 4672.50 days (High)
Frequency: 120.50 purchases (Very High)
Monetary: 55312.69 (Very High)
Number of Customers: 8 (Smallest cluster)
Conclusion: This cluster is characterized by very high frequency and monetary values, despite having a high recency. This indicates that these are very high-value customers with a lot of past transactions. The small number of customers might suggest they are significant but rare.

Cluster 2:

Recency: 4915.03 days (Very High)
Frequency: 1.55 purchases (Very Low)
Monetary: 476.66 (Low)
Number of Customers: 1060
Conclusion: Customers in this cluster have not purchased frequently and have spent relatively little. The high recency suggests they have not made recent purchases. This cluster might represent a group of one-time or very infrequent buyers.

Cluster 3:

Recency: 4674.00 days (High)
Frequency: 42.83 purchases (High)
Monetary: 190863.46 (Very High)
Number of Customers: 6 (Small cluster)
Conclusion: This cluster has a high frequency and monetary value, similar to Cluster 1, but with a slightly different profile. These are also high-value customers, but the cluster is very small.

Cluster 4:

Recency: 4681.47 days (High)
Frequency: 20.85 purchases (Moderate)
Monetary: 12400.28 (Moderate)
Number of Customers: 225
Conclusion: This cluster has moderate values for frequency and monetary spend, with a high recency. It represents customers who purchase moderately but have not bought recently.

Summary
High-Value Customers: Clusters 1 and 3 have very high monetary values and high frequency, indicating they are your most valuable customers. However, Cluster 1 is larger in terms of the number of customers than Cluster 3.

Low-Value Customers: Clusters 0, 2, and 4 have lower monetary values and frequencies. Cluster 0 is the largest but with the lowest metrics, while Cluster 2 has the lowest frequency and monetary values.

Actionable Insights:

For High-Value Customers: Consider targeting Clusters 1 and 3 for exclusive offers or loyalty programs to retain them.
For Low-Value Customers: Implement strategies to increase engagement and purchases, such as personalized marketing or special promotions.
For Inactive or Low-Frequency Customers: Re-engage them with tailored campaigns to bring them back to active status.
