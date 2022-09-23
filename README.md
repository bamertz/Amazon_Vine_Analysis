# Amazon_Vine_Analysis

## Overview

The purpose of this project was compare the Amazon Vine Program Reviews (Paid) to the non-Vine Reviews (Unpaid). The Amazon Vine Program is "an invitation-only program which selects the most insightful reviewers in the Amazon store to serve as Vine Voices. Vine Voices have the unique opportunity to order items free of charge and share their product experiences with Amazon customers to help them make informed buying decisions."

This analysis was conducted using the following:

* PySpark/Google Collab - To perform the ETL process.
* AWS RDS - To serve as the relational database.
* PostgreSQL/pgAdmin - To initialize the tables.
* Python Pandas Library (Jupyter Notebook) - To conduct analysis.

## Results

* Total Home Improvement Product Reviews Analyzed: 263,781
* Reviews with a minimum of 20 votes and at least 50% of those votes being marked as "helpful votes" were used to collect the following data:

### Vine Reviews (Paid)
* Vine Reviews: 266
* 5 Star Vine Reviews: 125
* 5 Star Vine Review Percentage: 46.99%
* 4 Star Vine Review Percentage: 29.32%
* 1 Star Vine Review Percentage: 2.63%
* Average Vine Review Rating: 4.12

### non-Vine Reviews (Unpaid)
* non-Vine Reviews: 38,829
* 5 Star non-Vine Reviews: 18,246
* 5 Star non-Vine Review Percentage: 46.99%
* 4 Star non-Vine Review Percentage: 15.94%
* 1 Star non-Vine Review Percentage: 21.25%
* Average non-Vine Review Rating: 3.61


## Summary
Initially I didn't see any bias in the ratings because the Vine Reviews and the non-Vine Reviews had a 46.99% 5 Star Review Percentage. However, the average Vine Review Rating was 4.12 while the non-Vine Review Rating was just 3.61. This indicates that their may be more bias in the Vine (or Paid) Reviews than originally believed. Looking closer, we can see that the Vine Reviews had a 4 Star Review Percentage of 29.32% while the non-Vine Reviews was just 15.94%. The bias really begins to show when looking at 1 Star Reviews, the Vine Reviews had just 2.63% whereas the non-Vine Reviews was all the way up to 21.25%. 

In conclusion, the Vine Review Program does create bias. 

Additional Analysis: A visualization could be created with all star ratings (1-5) such as a bar chart or pie-chart for both the Vine Reviews and non-Vine Reviews to see how large of a bias the Vine Program has. There should be further study into how helpful the Vine Reviews are in comparison to the non-Vine Reviews. 

All studies may suggest that the Amazon Vine Program is a good program for sellers to participate in if there is positive bias on each conclusion.

