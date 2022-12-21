# Amazon_Vine_Analysis

# Overview
The main purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. In this project, PySpark has been used to perform ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Additionaly, PySpark has been used to determine bias toward favorable reviews from Vine members.

# Results

Vine Reviews:
- The total number of vine reviews is 1266.
- Vine reviews with 5-star rating are 432.
- The percentage of 5-star vine reviews is 34.12.

Non-vine Reviews:
- Number of non-vine reviews is 62028.
- Non-vine reviews with 5-star rating are 29982.
- Lastly, the percentage of non-vine reviews with a 5-star rating is 48.34.

# Summary
The number of unpaid-vine reviews is much higher than the paid vine reviews program. Therefore, the bias is towards un-paid vine reviews. Furthermore, we can analyze whether the review purchase is verified or non-verified.
