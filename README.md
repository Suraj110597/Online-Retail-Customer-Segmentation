# Online-Retail-Customer-Segmentation

![image](https://user-images.githubusercontent.com/66847170/138936000-142b3472-995d-4c44-bf6c-8dada753b277.png)

# Problem Statement

In this project, the task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

# Approach
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?

Frequency – How often do they purchase?

Monetary Value – How much do they spend? 

A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer

# Segmentation with K-means clustering:
Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.

# Conclusion
After forming 4 clusters by k-means and elbow method we can separate our customers as star, light, new, lost. An ideal customer should have low recency , high frequency and high monetary value. These customers can now be targeted according to business need resulting in better customer relationships and profitability.

